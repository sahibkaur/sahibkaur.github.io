---
layout: post
title: "Training day 3 - UseRef"
author: "Sahibee"
---


Heloo people!!
Today I worked on the hook useRef() from [this tutorial](https://youtu.be/t2ypzz6gJm0?si=R9NfriVlazyhwj5p) and [Manipulating the DOM wtih refs](https://react.dev/learn/manipulating-the-dom-with-refs).

I am encountering an error now, here's the code:

```
export default function Theme() {

    const [name, setName] = useState('');
    const inputRef = useRef(null);

    function handleClick() {
        inputRef.current.focus();
    }

    return (
        <>
            <input ref={inputRef} value={name} onChange={e => setName(e.target.value)}/>
            <div>My Name is {name}</div>
            <button onClick={handleClick}>Focus</button>
        </>
    )
}
```

I get the error at the code snippet:
`inputRef.current.focus();`
 
 That `'inputRef.current' is possibly 'null'.` I got stuck here, I am keeping it on hold for now and moving on the next hook.

See you tomorrow for the next hook.

Toodles!
