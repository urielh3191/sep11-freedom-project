# || **11/25/2024** || Entry 1
# Purpose

The purpose of this project is to make my life more easier. Some problems I aim to fix are:
* forgetting important dates
* seeing home visitors at a glance
* weather at a glance

I will be using a mix of different API's (application programming interfaces) and my tool, vue.js. [vue.js](https://vuejs.org/guide/quick-start.html) is a tool that can be used to create placeholders on a website, and update the value in real time. *What?*, you might be asking. If for example, I set a placeholder (vue.js calls it an app) on my website called **clock**, and get a API to send me the actual time right now, the placeholder would update in real time with the actual time.


# Code
To start off, I needed to install vue.js. According to the website, all I needed to do was paste ```<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>``` into the ```<head>``` tags of any HTML document. And just like that, vue.js is installed.

Now that vue.js is installed, we can tinker around with the [quick start code](https://vuejs.org/guide/quick-start.html#using-vue-from-cdn) generously provided by the developers of vue.js, which is pretty basic. I just changed the names to better fit my purposes on my website.
```html
<div id="app">{{ message } </div> // message is the parameter of the app. You can change all instances of "message" and change it's name.

<script>
  const { createApp } = Vue // this is the name of the placeholder / variable

  createApp({
    data() {
      return {
        message: 'Hello Vue!' // this is the content / text that will be shown anytime "Vue" is called.
      }
    }
  }).mount('#app')
</script>
```
[Next Entry](entry02.md)

[SEP11 FP Homepage](../README.md)
