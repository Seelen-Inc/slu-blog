# **常见问题**

## **常见问题**

### **什么是Seelen UI？**

Seelen UI是一个桌面应用程序，可允许您自定义Windows 10/11体验。
它提供了广泛的主题，小部件和插件，以增强您的桌面环境。

---

### **Seelen UI是免费软件吗？**

是的，Seelen UI是一个免费软件。 您可以免费下载并使用Seelen UI。

---

### **Seelen UI会修改我的操作系统吗？**

不，**Seelen UI不会修改您的操作系统**。
它通过订阅Windows的本机事件并将其解释为显示适当的内容而起作用。 Seelen
UI读取系统设置并将其扩展在其自身的设置中，但是**不会更改或修改任何核心系统文件或注册表条目**。
该应用程序严格遵守Windows API，并且仅以Windows本身允许的方式与系统进行交互。

---

### **Seelen UI可以打破我的操作系统吗？**

不，**Seelen UI无法破坏您的操作系统**。
由于它不会修改任何核心系统文件或设置（如上一个问题所述），因此没有造成OS损坏的风险。
Seelen UI旨在在Windows API的边界内无缝地工作，从而确保安全稳定的体验。

---

### **Windows更新可以断开Seelen UI吗？**

不，**不太可能**标准的Windows更新将破坏Seelen UI。
但是，总是有很小的风险，尤其是当您使用**实验性构建**就像Windows
Insider构建一样。 这些构建通常包括未完成或不稳定的变化，可能会影响Seelen
UI等第三方应用程序。 为了获得最稳定的体验，建议使用稳定的Windows版本。

---

### **Seelen UI是否需要互联网连接才能工作？**

不，**Seelen UI不需要互联网连接**功能。 安装后，该应用程序的离线功能非常好。
但是，您将需要互联网连接到：

- 下载新**小部件**，，，，**插件**， 或者**主题**来自官方存储库。
- 检查该应用程序或其组件的更新。

除了这些活动之外，Seelen UI可以独立运行而无需互联网连接。

---

### **如何下载Seelen UI？**

您可以从[官方网站](https://seelen.io)。

## **常见的用户问题**

### **灰色/深屏问题**

使用Seelen UI时，一些用户会体验灰色或深色屏幕。
这个问题通常是由修改Windows外观的第三方应用程序引起的，例如**云母**。

**解决方案**：

- 禁用这些类型的应用程序。
- 如果应用程序允许，请将Seelen UI添加到排除列表中以防止冲突。

---

### **系统托盘无法正常工作**

如果Seelen
UI中的系统托盘无法正常运行，则可能是由于与修改Windows任务栏的第三方应用程序发生冲突，例如**Start11**，，，，**Startallback**，或类似的工具。

**为什么会发生这种情况？**\
Seelen UI的托盘模块需要访问**托盘溢出**正常工作。 这些应用程序可能会干扰此功能。

**解决方案**：

- 在使用SEELEN UI之前，请禁用或卸载任何第三方任务栏修改工具。
- 确保Seelen UI可以完全访问本机系统托盘。

---

### **AHK触发的反陈词**

一些反陈词系统可能会检测到的使用**Autohotkey（AHK）**，Seelen
UI依赖于快捷方式，这是一种潜在的作弊。

**解决方案**：

- 在使用反作用系统启动游戏之前，禁用Seelen UI的快捷方式。
- 完成游戏后，可以重新启用快捷方式。
