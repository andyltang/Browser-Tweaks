# ❓ What is this?
Here are tweaks that change the website UI by injecting scripts that overrides existing styles. This is can be utilized by any browser with the capability of injecting scripts. Generally, this is done through browser extentions.  

## 🛠️ Installation

### CSS Injection
1. Install a CSS injection extension. I would recommend [Stylus](https://github.com/stylus/stylus) as a trustable injector. It is forked from Stylish with the focus on [open source and no telemetry](https://github.com/openstyles/stylus/wiki/FAQ#what-are-the-main-differences-and-improvements-over-the-original-stylish-add-on)
2. After installation, the browser will be able to detect `*.user.css` files in the browser
3. Find the `user.css` file in the repo you want to install and click on `Raw`
4. You will be brought to a Stylus page. On the top left, you can click `Install`
## 🧩 Compatibility

Tested on Zen Browser only and it is also expected to work on Firefox and forks since they use the same engine. Other browsers such as Chromium based ones which can install a script injector can also work except for some edge cases when it comes to how each engine handles styles.
