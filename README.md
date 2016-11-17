# [Thing Translator](https://oxism.com/thing-translator/)
### [An AI Experiment](https://aiexperiments.withgoogle.com/)
✨ [Try the live demo here.](https://oxism.com/thing-translator/) ✨

![](https://oxism.com/thing-translator/thing-translator.gif)

![](https://lh3.googleusercontent.com/khbjth0AxLYjz8E74iSUkuFssohsIG5qIQ-8x0PXOieEm0wm-g98OFFS0TURr6-381CsKGI7iSxahUKm6PcyoV4rxHClvZ67UA=s640)

![](https://lh3.googleusercontent.com/9egZnC80nRDa9tMJrL079ClkeSdyfjMp0I4UQgjRFKb1uZmHM3Gdtk-q859HEBOUA2jaF64SSeQsGnrnWIkZ4iCfu0uzWg3Nfw=s640)
---

Thing Translator is a web app that lets you point your phone (or laptop) at
stuff to hear to say it in a different language. It was developed as part of
Google's [AI Experiments](https://aiexperiments.withgoogle.com/) project.

Behind the scenes Thing Translator is using Google's
[Cloud Vision](https://cloud.google.com/vision/) and
[Translate](https://cloud.google.com/translate/) APIs.


### Development

To start a development server on `9966` that will watch for code changes simply run:
```
$ npm run dev
```

To optimize the output for production run:
```
$ npm run bundle
```

### Notes

Unfortunately this experiment does not work on iOS or desktop Safari (at least
until Apple allows camera access from the web).

Forked from the original project by dmotz. Attempting to integrate with Android.
- con-ji 2016
