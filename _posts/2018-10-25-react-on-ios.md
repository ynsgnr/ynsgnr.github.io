---
layout: post
title: How to code run react native app on ios without recompiling
---

<p>Hello there, I have a little but very annoying problem with ios devices while working with react-native. Not being able to set a dynamic ip on the go without recompiling the application.</p>

<h2>The Problem</h2>
<p>I have to recompile for ios everytime I changed a network, which happens a lot since I love working in different places. Also finding a cable, launcinh the simulator (yes I work with a windows computer and I love windows!), and then launching xcode and waiting to recompile feels like an etternity. Also there is some networks you can not just connect like eduroam. They block traffic between clients for security reasons. In those cases its almost impossible to work with react native on iOS.</p>

<h2>The Solution</h2><
<p>Solution is to start running a custom hotspot and forcing computer with the packager to get a predefined IP from its own hotspot. Wındows 10 and MacOSX has built in hotspots already!<p/>
