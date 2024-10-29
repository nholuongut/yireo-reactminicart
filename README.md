# React minicart for Magento 2 Knockout-based frontend

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

This module offers a React-based minicart to replace the existing minicart of Magento itself. Please note that this is an experiment to show how easy it is to build React components. It could be used on live sites, but comes without warranties.

### Installation
Before you install this module, make sure to install the [Yireo_React](https://github.com/nholuongut/yireo-reactminicart) module first. An install via `composer` should pick this up right away.

Use the following commands to install this module into Magento 2:

    composer config repositories.yireo-react vcs git@github.com:yireo-training/Yireo_React.git
    composer config repositories.yireo-react-minicart vcs git@github.com:yireo-training/Yireo_ReactMinicart.git
    composer require yireo/magento2-react-minicart:dev-master
    
    bin/magento module:enable Yireo_React Yireo_ReactMinicart
    bin/magento setup:upgrade

Make sure to read the **Usage** section below as well.

### Usage
This module adds an additional minicart to the Magento 2 frontend, based upon ReactJS, and it removes the old component. This requires the source to be compiled into generic JS code. To compile the source, follow the procedure of `Yireo_React` to compile the sources from the root of Magento:

    yarn dev

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟