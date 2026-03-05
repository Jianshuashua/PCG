# PCG
 Professional Houdini Digital Assets (HDAs) for Game Development. Optimized for Unreal Engine &amp; Unity. (Procedural Modeling, Terrain, &amp; Optimization Tools).

# Quick Brush - Installation & Licensing Guide (V2.0)

### 1. Plugin Installation / 插件安装
> **Note:** Please ensure Houdini is closed before installation.  
> **注意：** 请在安装前确保 Houdini 处于关闭状态。

* **A. HDK SOP (DSO)**
    * **EN:** Choose the folder matching your Houdini version (19.0 - 21.0). Copy the core library file to the `dso` directory.
    * **CN:** 根据您的 Houdini 版本选择对应的文件夹。将核心库文件复制到 `dso` 目录下。
    * **Files / 文件:** `HDK_Sop.dll` (Windows) / `HDK_Sop.so` (Linux)
    * **Windows Path:** `C:\Program Files\Side Effects Software\Houdini [Version]\houdini\dso`
    * **Linux Path:** `/opt/hfs[Version]/houdini/dso`

* **B. VEX Functions**
    * **EN:** Copy the VEX extension file to the `dso/vex` subdirectory.
    * **CN:** 将 VEX 扩展文件复制到 `dso` 下的 `vex` 子目录中。
    * **Files / 文件:** `VEX_Function.dll` (Windows) / `VEX_Function.so` (Linux)
    * **Windows Path:** `C:\Program Files\Side Effects Software\Houdini [Version]\houdini\dso\vex`
    * **Linux Path:** `/opt/hfs[Version]/houdini/dso/vex`

* **C. Asset Files (OTLs)**
    * **EN:** Copy the `otls` folder to your Houdini user preferences directory.
    * **CN:** 将压缩包中的 `otls` 文件夹复制到 Houdini 用户配置目录下。
    * **Windows Path:** `Documents\houdini[Version]\otls`
    * **Linux Path:** `~/houdini[Version]/otls`

---

### 2. Trial Version / 试用说明 (Optional)
* **EN:** The hda_license.json file located in PCG/otls/ is the license for the trial version. To use it, simply copy this file to your Houdini user configuration directory. This license is updated periodically; if it expires before an update is posted, please contact jian_shua_shua@qq.com.
* **CN:** PCG/otls/下的 `hda_license.json` 是试用版本的授权license文件，文件复制到 Houdini 用户配置目录下即可，该文件会定期更新，如果过期未更新请联系：jian_shua_shua@qq.com。
* **Path:** `Documents\houdini[Version]\` (Windows) or `~/houdini[Version]/` (Linux)

---

### 3. Get Full License / 获取正式授权
* **Step 1: Generate Code / 生成申请码**
    * **EN:** Open Houdini and create a **Quick Brush** node. Once the node calculates (triggers), an Application Code will pop up automatically.
    * **CN:** 打开 Houdini 并创建一个 **Quick Brush** 节点。当节点触发计算时，会自动弹出 Application Code（申请码）。
* **Step 2: Send Email / 发送邮件**
    * **EN:** Copy the code and send it to: `jian_shua_shua@qq.com`
    * **CN:** 复制该代码并发送至邮箱：`jian_shua_shua@qq.com`
* **Step 3: Receive License / 接收授权**
    * **EN:** I will reply with your license file (`hda_license.json`) within 24 hours.
    * **CN:** 我会在 24 小时内回信并发送您的正式授权文件 (`hda_license.json`)。

---

### 4. Activate License / 激活授权
* **EN:** Place the received `hda_license.json` into your Houdini user preferences directory (overwrite the trial file if prompted).The Full Version License is hardware-locked (tied to your computer's unique hardware ID). An active internet connection is required for verification; this is strictly used to retrieve the current network time and does not collect any personal data.
* **CN:** 将收到的 `hda_license.json` 文件放入以下目录（如果已有试用版文件，请选择替换）。正式版本license授权是锁定计算机硬件的，并且电脑必须联网才能用（联网是为了获取互联网时间，不会收集任何个人信息）。
* **Windows Path:** `Documents\houdini[Version]`
* **Linux Path:** `~/houdini[Version]/`
* *(e.g. C:\Users\Name\Documents\houdini21.0\hda_license.json)*

---

### 5. Support & Feedback / 支持与反馈
* **EN:** For any bugs, compatibility issues, or suggestions, please contact me.
* **CN:** 如有任何 Bug、版本兼容性问题或改进建议，欢迎随时联系。

### [🚀 Get the Latest Release (v1.0.0)](https://github.com/Jianshuashua/PCG/releases/download/v1.0.0/JianShuaShua.rar)
### 📺 Product Demonstration (Demo Videos)


[![Watch the video](https://img.youtube.com/vi/cUmypxA_54k/0.jpg)](https://www.youtube.com/watch?v=cUmypxA_54k)
[![Watch the video](https://img.youtube.com/vi/piajC5W0aSE/0.jpg)](https://www.youtube.com/watch?v=piajC5W0aSE)
[![Watch the video](https://img.youtube.com/vi/jnFZ0hQKQcs/0.jpg)](https://www.youtube.com/watch?v=jnFZ0hQKQcs)
[![Watch the video](https://img.youtube.com/vi/KbvRJ8zGxmA/0.jpg)](https://www.youtube.com/watch?v=KbvRJ8zGxmA)
[![Watch the video](https://img.youtube.com/vi/qddz2Uq2gZU/0.jpg)](https://www.youtube.com/watch?v=qddz2Uq2gZU)
[![Watch the video](https://img.youtube.com/vi/2T3kU7mYKSE/0.jpg)](https://www.youtube.com/watch?v=2T3kU7mYKSE)


