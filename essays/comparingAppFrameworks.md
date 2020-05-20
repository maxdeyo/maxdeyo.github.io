---
layout: essay
type: essay
image: images/android_vs_ios.jpg
title: Native App Frameworks
date: 2020-05-20
labels:
  - React Native
  - Flutter
  - NativeScript
  - Xamarin
---

In evaluating the different options available to us when choosing a native app framework to use, there are a variety of factors to consider. First, what are the languages and frameworks the development kit is based on and how does that sync up with our team members skillsets? Second, what platforms are available to develop for and how easy is porting from platform to platform? Third, how active is the community and how much third party tools and help is there to pull from. Each language listed below has their own benefits and all of them are possible options.
I've made a small Google Sheet to show the different features of each. Anyone with a UH email can edit. Some of the sheet may be unclear or inaccurate due to third-party solutions.
(https://docs.google.com/spreadsheets/d/137Q3dlUc6_9NOkgH2uKdiUPDAf3X1_xyr-D9F60A0jU/edit?usp=sharing)

<H2>Xamarin</H2>
Honestly the least likely choice in my mind. Like most .NET products using Xamarin means learning unique Microsoft languages, including C# and XAML. Xamarin.Mac, Xamarin.iOS and Xamarin.Android all allow you to target individual OS's but it appears Xamarin.Forms is the only option which allows a shared logic and UI codebase but only across Android, iOS and Windows. Xamarin.Forms claims to be free and open-source but apparently the overall platform charges for enterprise. The headaches of learning an entirely new language, markup language and framework seems to be too much, and uncertainty over price doesn't help.

<b>Apps developed with Xamarin:</b> UPS, Alaska Airlines, Outback Steakhouse

<H2>NativeScript</H2>
Whereas all other options here are developed by big names like Facebook, Microsoft and Google, NativeScript is developed by..... Telerik by Progress. While NativeScript claims great first and third-party support, it is much less well known than the other and I am a little worried about long-term support. For comparison, Nativescript has 18.5k stars on Github while React Native and Flutter both have about 90k. Still, NativeScript checks a lot of boxes. It uses JavaScript or TypeScript with CSS and looks like you can build Web apps and PWA's from the same codebase as Android and iOS. The only other gripe is that it uses either Angular or Vue but not React. This really doesn't seem like that big of a hill to climb, Vue is apparently relatively easy to learn and use.

<b>Apps developed with NativeScript:</b> Sennheiser Smart Control, MyPUMA

<H2>Flutter</H2>
Flutter is an open source sdk created by Google and can be used to build apps for Android, iOS, the Web, Windows, Mac and Linux. Developing for Flutter somewhat stands on its own from all the others, as all the styling and markup is built in to its unique language Dart. Dart is heavily influenced by Javascript and is strongly-typed like TypeScript. Like React Native, Flutter has strong 3rd party support and is developed by a massive corporation(though Google is somewhat notorious for side-project failures). Flutter is one of my top choices and if the overhead of learning Dart isn't too big of an issue, this could be the best choice. 

<b>Apps developed with Flutter:</b> Alibaba, Groupon, Realtor.com

<H2>React Native</H2>
React Native is the only framework here I have any experience with(though admitately not much). Transitioning from React to React Native is super smooth and the built in component library looks and works great. There is support for TypeScript and the built-in alternative Flow. Since both are maintained by Facebook React Native stays pretty closely in sync with Reacts updates(which means hooks). Web dev only seems to be supported through third-party but works well enough. The biggest issue here is developing cross-platform can mean a lot of double-checking to make sure it works for each platform(especially if using native features). This is my top choice 
Also Expo is a great developer tool worth noting. It makes initializing easy, sharing easy, adds a bunch of features and makes builds and hot reloading easy(just scan a qr code on your phone and you can test it from their app). It does however, limit the native features and third-party tools you can use and can be difficult to eject if you need to remove it. It's probably wise to use React Native without Expo but it's something to consider.

<b>Apps developed with React Native:</b> Instagram, Skype, Bloomberg

<H2>The Winner?</H2>
<img class="ui medium right floated image" src="../images/react-native.png">
React Native is my favorite choice. It fits well with the technologies we are aiming to use and has plenty third-party plugins to add on, if necessary. Using Expo to streamline development is a possibility that I think we should consider. 
That said, I don't think you can go wrong with any framework and the idea of learning Flutter or NativeScript excites me.
