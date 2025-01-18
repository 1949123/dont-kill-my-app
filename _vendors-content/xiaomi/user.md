---
制造商：
-小米

---

###应用固定/应用锁定

打开最近应用程序托盘时，向下拖动应用程序(将被锁定)。即使清除最近应用程序，锁定/固定的应用程序也将获得进一步保护且不会从后台清除。再次向下拖动以从背景中清除应用程序。<溴>
在某些手机上，您需要长按您的应用程序，然后从菜单中选择挂锁图标：

<div班级="img-block">
  <IMGsrc="/assets/img/xiaomi/locking.jpg">
</div>

另一种应用程序锁定方法隐藏得更深：

<div班级="img-block">
  <数字>
    <IMGsrc="/assets/img/xiaomi/xiaomi_lock_1.jpg">
    <figcaption>打开安全应用→提升速度</figcaption>
  </数字>

  <数字>
    <IMGsrc="/assets/img/xiaomi/xiaomi_lock_2.jpg">
    <figcaption>打开设置轮齿图标</figcaption>
  </数字>

  <数字>
    <IMGsrc="/assets/img/xiaomi/xiaomi_lock_3.jpg">
    <figcaption>进入锁定应用程序并选择您的应用程序</figcaption>
  </数字>

</div>



###自动启动权限

在MIUI14上，每个应用程序都有从后台启动的新权限，*设置-应用-您的应用-应用权限-后台自动启动*.

<div班级="img-block">
  <IMGsrc="/assets/img/xiaomi/miui14_autostart.png">

</div>

###增压速度

如果应用程序在此“加速”功能中被锁定，则可通过*超级省电器*.

<div班级="img-block">
  <IMGsrc="/assets/img/xiaomi/xiaomi_superator.jpg">
  <IMGsrc="/assets/img/xiaomi/xiaomi_super_2.jpg">
  <IMGsrc="/assets/img/xiaomi/xiaomi_super_3.jpg">

</div>



###MIUI优化

到目前为止，已在MIUI12上报告了MIUI优化，但旧版本上也可能存在此选项(如果您在手机上找到此选项，请告知我们)。它隐藏在开发者设置中，因此您需要首先切换到开发者模式(在关于手机中点击10次MIUI版本)。与所有“优化”一样，MIUI优化可以中断后台任务。

<div class="img-block">
  <img src="/assets/img/xiaomi/miui_optimization_1.jpg">
  <img src="/assets/img/xiaomi/miui_opti.gif">

</div>

There were some reports, that the MIUI optimization was missing in the menu - [here is a workaround guide](https://piunikaweb.com/2021/04/19/miui-optimization-missing-in-developer-options-try-this-workaround/).


### MIUI 12

To let your app run in the background, make sure settings for your app look like the following:

<div class="img-block">
  <img src="/assets/img/xiaomi/miui12_settings1.jpg">
  <img src="/assets/img/xiaomi/miui12_settings2.jpg">
  <img src="/assets/img/xiaomi/miui12_settings3.jpg">
  <figcaption> Some options might be missing for your app<br> (depends on the permissions the app needs). </figcaption>

</div>

### MIUI 11

To let your app run in the background, make sure settings for your app look like the following:

<div class="img-block">
  <img src="/assets/img/xiaomi/ss_miui11_batterysaversettings1.png">
  <img src="/assets/img/xiaomi/ss_miui11_batterysaversettings2.png">
</div>

### MIUI 10


To let your app run in the background, make sure your settings look like the following (here for example is Sleep as Android):


<div class="img-block">
  <img src="/assets/img/ss_xiaomi_1a.png">
  <img src="/assets/img/ss_xiaomi_1b.png">
  <img src="/assets/img/ss_xiaomi_1c.png">
</div>


### Power management


Please enable:

* *Settings > Advanced Settings > Battery manager > Power plan* is set to Performance

* *Device Settings > Advanced Settings > Battery Manager > Protected apps* – your app needs to be Protected

* *Device Settings > Apps > your app > Battery > Power-intensive prompt* and *Keep running after screen off*

* *Settings > Additional Settings > Battery & Performance > Manage apps’ battery usage* and here:

1. Switch Power Saving Modes to Off

2. Choose the next options: *Saving Power in The Background > Choose apps > select your app > Background Settings > No restrictions*


### App battery saver


*Security > Battery > App Battery Saver > your app > No restriction*


### Autostart

(according to [Xiaomi](https://in.c.mi.com/thread-253478-1-0.html):


Open *Security app > Permissions > Auto-start*


Enable "Autostart" for desired apps.

<div class="img-block">
  <img src="/assets/img/ss_xiaomi_as_1.png">
  <img src="/assets/img/ss_xiaomi_as_2.png">
    <div class="img-block">
     <figure>
          <img src="/assets/img/ss_xiaomi_as_3.png">
       <figcaption>Search for Your app and tap to enable</figcaption>
     </figure>
    </div>
</div>    


### Hidden settings

On some XiaoMi phones, several settings options are hidden from you. Luckily, there are several apps on Play Store designed specifically for revealing these secret options and menus.

* [**Hidden Settings For MIUI** from Yunus Ceyhan](https://play.google.com/store/apps/details?id=com.ceyhan.sets)

* [**MIUI Hidden Settings Activity Launcher, poco, note** from More by NetVor - Android Solutions](https://play.google.com/store/apps/details?id=com.netvor.hiddensettings)

* [**MQS - Quick Settings for MIUI** from Ruby Faick](https://play.google.com/store/apps/details?id=com.zonarmr.miuiengineermode)
