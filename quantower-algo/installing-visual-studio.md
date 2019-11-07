---
description: >-
  How to install Visual Studio and Quantower Algo extension, and create your own
  indicators and strategies
---

# Install for Visual Studio

**Visual Studio** - is an integrated development environment \(IDE\) from Microsoft, which includes a code editor with IntelliSense, debugger, supporting for source control systems and many other professional features. The currently supported Visual Studio version is 2017.

{% hint style="success" %}
We recommend you to use the most basic version of **Visual Studio — the Community edition**, which is available free of charge.
{% endhint %}

You can [download Visual Studio from official web site](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=15). It requires about 10 minutes to install and 2.5 Gb of free space on your hard drive.

Download web installer and run it. After initialization, you will be prompted to select the required components. For using with Quantower Algo extension we need only "NET desktop development" workload. You can uncheck optional components also, to reduce installation size:

![Minimal required installation](../.gitbook/assets/screenshot_1dd.png)

Continue installation and in a few minutes, after downloading and applying required packages, Visual Studio will start automatically:

![Default view of Visual Studio 2017](../.gitbook/assets/default-view-of-visual-studio.png)

Now we need to install Quantower Algo extension from Visual Studio Marketplace. Use "_**Tools -&gt; Extension and Updates...**_" main menu item to open Extensions Manager. Type "_**Quantower**_" into the search box of **Online tab** and you will find a required extension:

![Extensions and Updates window](../.gitbook/assets/extensions-manager.png)

Click "**Download**". Visual Studio will ask you for restarting to finish the extension installation process.

To check whether Quantower Algo is installed successfully click "_**File -&gt; New -&gt; Project**_" menu item and you will see special project types: Indicator and Strategy:

![](../.gitbook/assets/new-project-1%20%281%29.png)

Now everything is ready to [create your first indicator](simple-indicator.md).

