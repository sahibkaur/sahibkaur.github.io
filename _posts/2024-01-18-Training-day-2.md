---
layout: post
title: "Training day 2 - UseMemo"
author: "Sahibee"
---


Heyoo!!
Today I worked on the hook useMemo() from [this tutorial](https://youtu.be/THL1OPn72vo?si=DGo2eHMS-b_P6SMK).

Here, what we are trying to do is, we are doubling the number user enters in input but the output is supposed to show after a delay, using a slowFunction(we define ourselves). There's also a functionality to change the theme but the delay occurs while changing theme as well. We don't want that, so we can use useMemo() which helps to check if the number remains same (that is we don't need to double it), then we don't have to call the slowFunction. 
In other words, useMemo() is used to memorize the previous value and makes sure unnecessary operations don't take place, like the slowFunction.

We also tried to use the hook to keep the themeStyles object same as follows:

```
    useEffect(() =>  useMemo( () =>  {
        console.log("Theme changed");
    }, [themeStyles])
    , [dark]);
```

But then I tried to deploy the code, I got this error.

```Error: React Hook "useMemo" cannot be called inside a callback. React Hooks must be called in a React function component or a custom React Hook function```

According to [this post](https://blog.logrocket.com/understanding-common-frustrations-react-hooks/), I am breaking the [rules of hooks](https://legacy.reactjs.org/docs/hooks-rules.html).

Oops! I got it. I was supposed to use the useMemo hook while defining the themeStyles object, like this:

```
    const themeStyles = useMemo (() => {
        return {
        backgroundColor: dark ? '#2D2D2A' : '#E5DCC5',
        color: dark ? 'white': '#2D2D2A'
        }
    }, [dark]);

    useEffect(() =>  {
        console.log("Theme changed");
    }, [themeStyles]);
```

Here's the [output](https://demo-hooks-eqovxyanx-sahibkaur.vercel.app/) and [the code](https://github.com/sahibkaur/demo-hooks/pull/1/commits/133fa63a4b57717430e2f384ab68a208e2417c29).

See you tomorrow for the next hook.

Toodles!
