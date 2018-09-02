# OruxMaps

**OruxMaps** 可以查看在线、离线地图，可以查看导入的航迹文件，可以利用手机的各类传感器记录航迹信息，以供后期使用。

本章主要介绍观星准备中需要用到的基础功能，包括：离线地图、航迹跟踪、航迹记录、路点标记等。此外OruxMaps还有许多高级功能，可访问[官方文档](http://www.oruxmaps.com/oruxmapsmanual_zh.pdf "OruxMaps中文文档")查看。

---

## 获取App

OruxMaps可以从官网下载点下载，目前（2017年9月6日）版本为`v.7.1.4`。若您发现了新版本，可[通知作者](https://github.com/konrumi/stargazer/issues/new "提出Issues")更新此文章。

- [官网下载地址](http://www.oruxmaps.com/OruxMaps7.1.4.apk "OruxMaps v.7.1.4 官网下载")
- [百度网盘下载地址](https://pan.baidu.com/s/1ge2t6mv "OruxMaps v.7.1.4 百度网盘下载") // 密码: `akk9`

---

## 基础功能

首先，需对OruxMap App的面板和基础功能进行介绍。

![基础功能](https://i.loli.net/2018/09/01/5b8a90f55f921.png)

### ① 顶部菜单

从左到右依次是：

1. **轨迹** ：包含GPS与记录航迹相关的选项；
2. **路点** ：包含路点相关的选项；
3. **航迹/路径** ：包含管理航迹/路径的相关选项；
4. **地图** ：包含地图的相关选项；
5. **设置** ：包含各种设置和其他选项；

### ② 状态

以图标的形式显示当前启用的功能。

### ③ 左侧快捷按钮栏

左侧的快捷按钮（可配置），从上到下依次是：

1. **放大** ；
2. **缩小** ；
3. **重置缩放** ；
4. **航迹信息** ；
5. **路点信息** ；

### ④ 右侧快捷按钮栏

左侧的快捷按钮（可配置），从上到下依次是：

1. **开启/关闭GPS** ；
2. **开启/关闭手动定位** ；
3. **开始/停止航迹记录** ；
4. **新增路点** ；
5. **距离测量工具** ；

### ⑤ 仪表盘

以数据窗格的形式，显示当前的各种运动信息。

---

## 地图

OruxMaps作为一个户外地图App，提供的最主要功能便是地图功能。本节主要介绍OruxMaps的以下地图功能：

- 下载、安装离线地图；
- 添加地图；
- 使用3D地图；

### 离线地图下载

在野外调查时，难免会进入没有信号的地区，因此推荐预先安装不依赖网络的离线地图。

OruxMaps官网提供了许多地图来源，可参见[地图下载页](http://www.oruxmaps.com/cs/en/maps "OruxMaps地图下载")。本书中，推荐[OpenAndroMaps](https://www.openandromaps.org/en/downloads "OpenAndroMaps")提供的矢量离线地图。当然。您也可以根据需求与喜好自行选择。

> OpenAndroMaps地图的优势：
> - 包含中国地区；
> - 适量地图，支持放大查看细节；
> - 带有等高线，支持查看地形；
> - 支持多语言，带有中文地名；

离线地图的安装方法主要有两种—— **在APP中下载安装离线地图** 、 **在PC下载离线地图传至手机安装** 。

#### 在APP中下载安装离线地图

在OruxMaps App内，可直接下载OpenAndroMaps地图。但是由于各种原因，如果下载失败，清尝试通过PC下载。

点击右上角的 **地图** 按钮，在弹出菜单中，选择 **切换地图** 。

![在APP中下载安装离线地图](https://i.loli.net/2018/09/01/5b8a90f514d18.png)

点击右上角的 **⊕（添加）** 按钮。

![在APP中下载安装离线地图](https://i.loli.net/2018/09/01/5b8a90f533b31.png)

在最后的 **World** 中，选择 **OpenAndroMaps** 。

![在APP中下载安装离线地图](https://i.loli.net/2018/09/01/5b8a90f53732d.png)

选择后，将进入APP浏览器访问OpenAndroMaps网站。用户需要分别下载 **主题文件** 与 **地图文件** 。后续的步骤与PC下载类似，因此请参考下面的PC教程。

---

#### 在PC下载离线地图传至手机安装

#### 下载地图

为正确显示等高线等信息，需下载配套的 **主题文件：Elevate** 。

访问 **[OpenAndroMaps官网](https://www.openandromaps.org/en/downloads "OpenAndroMaps")** ，进入 **[Elevate主题文件下载页](https://www.openandromaps.org/en/legend/elevate-mountain-hike-theme "Elevate下载")** 。

![在PC下载离线地图传至手机安装](https://i.loli.net/2018/09/01/5b8a90f56956b.png)

若希望使用App安装，点击左侧的 **OruxMaps** ；若希望在PC下载，点击右侧的 **Normal Version** 。

![在PC下载离线地图传至手机安装](https://i.loli.net/2018/09/01/5b8a90f535921.png)

若在App内下载，则安装应该能够自动完成。若正常下载，则您应当得到一个Zip压缩包。

解压缩后，将得到的文件存入手机的 `../oruxmaps/mapstyles/` 目录下即可。连接手机可通过各种软件完成，如 **[豌豆荚](http://www.wandoujia.com/)** 等。为了将手机连接至电脑，你可能需要启用手机的USB调试模式。

> 注：在安装手机管理软件时，请务必注意甄别安装来源和选项，以免对个人手机电脑、手机造成负面影响。

![安装地图样式](https://i.loli.net/2018/09/01/5b8a90f555336.png)

![安装地图样式](https://i.loli.net/2018/09/01/5b8a90f5388a7.png)

安装完成后，打开OruxMaps App，点击右上角的 **地图** 按钮，在弹出菜单中，选择 **Map tweaks（调整地图）** 。

![安装地图样式](https://i.loli.net/2018/09/01/5b8a90f530a14.png)

在弹出菜单中，选择 **OSM主题** ，然后选择刚安装的 **Elevate** 主题即可。

![安装地图样式](https://i.loli.net/2018/09/01/5b8a90f513679.png)

![安装地图样式](https://i.loli.net/2018/09/01/5b8a91980f0b3.png)

---

#### 安装地图

准备好样式文件后，即可下载安装地图文件。

访问 **[OpenAndroMaps官网](https://www.openandromaps.org/en/downloads "OpenAndroMaps")** ，进入 **[地图文件下载页](https://www.openandromaps.org/en/downloads/countrys-and-regions "地图文件下载")** 。

![在PC下载离线地图传至手机安装](https://i.loli.net/2018/09/01/5b8a919846407.png)

在地图文件下载页，选择希望下载的目标区域，这里选择 **[亚洲/中东区域](https://www.openandromaps.org/en/downloads/asia-middle-east "亚洲/中东区域")** 。

![在PC下载离线地图传至手机安装](https://i.loli.net/2018/09/01/5b8a91984d6fe.png)

在列表中，选择调查区域所述的位置，如 **中国北方** ，随后在展开的页面中选择下载。另外，也应该下载 **Poi包** 。

若在App内下载，则安装应该能够自动完成。若正常下载，则您应当得到一个地图Zip压缩包和PoiZip压缩包。

![在PC下载离线地图传至手机安装](https://i.loli.net/2018/09/01/5b8a91983ebfb.png)

解压缩后，将地图文件和Poi文件存入手机的 `../oruxmaps/mapfiles/` 目录下即可。

![在PC下载离线地图传至手机安装](https://i.loli.net/2018/09/01/5b8a91981931d.png)

安装完成后，打开OruxMaps App，点击右上角的 **地图** 按钮，在弹出菜单中，选择 **切换地图** 。

![在PC下载离线地图传至手机安装](https://i.loli.net/2018/09/01/5b8a919812594.png)

在弹出界面中，选择上方的 **OFFLINE** ，再选择刚刚安装的 **CHINA-NORTH_ML(MAPSFORGE)** 地图即可。

![在PC下载离线地图传至手机安装](https://i.loli.net/2018/09/01/5b8a919813d57.png)

---

### 添加地图

#### 配置在线地图

除了默认提供的地图外，OruxMaps也支持我们自定义地图来源，此处以Google Earth地图为例。

野外调查中，除了矢量的离线地图以外，我们往往还需要更能体现当地自然环境的卫星地图。Google Earth是目前比较成功的卫星地图提供商。虽然Google的许多产品由于众所周知的原因在大陆并不可用，但是我们仍然可以使用Google Maps CN提供的服务，只需要把Google的地图来源添加到OruxMaps中即可。

OruxMaps使用 `onlinemapsources.xml` 文件管理在线地图的来源。我们可以在其中加入以下3个Google Maps CN的地图源。

如果觉得麻烦，你也可以直接下载编辑好的 [`onlinemapsources.xml`](../asset/map-tools/oruxmaps/onlinemapsources.xml) 。

```xml
<onlinemapsource uid="0">
    <name>Google Maps</name>
    <url><![CDATA[http://mt{$s}.google.cn/vt/lyrs=m@121&hl={$l}&x={$x}&y={$y}&z={$z}]]></url>
    <minzoom>0</minzoom>
    <maxzoom>19</maxzoom>
    <projection>MERCATORESFERICA</projection>
    <servers>0,1,2,3</servers>
    <httpparam name=""></httpparam>
    <cacheable>1</cacheable>
    <downloadable>1</downloadable>
    <maxtilesday>0</maxtilesday>
    <maxthreads>0</maxthreads>
    <xop></xop>
    <yop></yop>
    <zop></zop>
    <qop></qop>
    <sop></sop>
</onlinemapsource>

<onlinemapsource uid="1">
    <name>Google Earth</name>
    <url><![CDATA[http://www.google.cn/maps/vt?lyrs=s@168&x={$x}&y={$y}&z={$z}]]></url>
    <minzoom>0</minzoom>
    <maxzoom>20</maxzoom>
    <projection>MERCATORESFERICA</projection>
    <servers>0,1,2,3</servers>
    <httpparam name=""></httpparam>
    <cacheable>1</cacheable>
    <downloadable>1</downloadable>
    <maxtilesday>0</maxtilesday>
    <maxthreads>0</maxthreads>
    <xop></xop>
    <yop></yop>
    <zop></zop>
    <qop></qop>
    <sop></sop>
</onlinemapsource>

<onlinemapsource uid="2">
    <name>Google Terrain</name>
    <url><![CDATA[http://mt{$s}.google.cn/vt/lyrs=t,r&hl={$l}&x={$x}&y={$y}&z={$z}]]></url>
    <minzoom>0</minzoom>
    <maxzoom>15</maxzoom>
    <projection>MERCATORESFERICA</projection>
    <servers>0,1,2,3</servers>
    <httpparam name=""></httpparam>
    <cacheable>1</cacheable>
    <downloadable>1</downloadable>
    <maxtilesday>0</maxtilesday>
    <maxthreads>0</maxthreads>
    <xop></xop>
    <yop></yop>
    <zop></zop>
    <qop></qop>
    <sop></sop>
</onlinemapsource>
```

完成后，将添加了Google地图源的 `onlinemapsources.xml` 文件放入 `../oruxmaps/mapfiles/` 目录下即可。

> 注：每次OruxMaps升级后，都会创建一个新的 `onlinemapsources.xml` ，而旧的 `onlinemapsources.xml` 会被重命名为 `onlinemapsources.xml.bak` 文件保存在相同位置。升级后请手动替换 `onlinemapsources.xml` 文件。

![添加地图](https://i.loli.net/2018/09/01/5b8a91983c1de.png)

完成后，打开OruxMaps App，点击右上角的 **地图** 按钮，在弹出菜单中，选择 **切换地图** 。

![添加地图](https://i.loli.net/2018/09/01/5b8a91981566d.png)

在弹出界面中，选择上方的 **刷新** ，刚刚添加的Google地图应该就会出现在列表中。

![添加地图](https://i.loli.net/2018/09/01/5b8a919816ca6.png)

---

#### 离线存储地图图块

选择Google Earth地图后，我们即可在线查看Google Earth卫星地图了。但是在野外调查中，时常遇到没有信号的情况，因此我们也可以预先下载地图图块，作为离线地图。

![添加地图](https://i.loli.net/2018/09/01/5b8a9234959cb.png)

打开OruxMaps App，点击右上角的 **地图** 按钮，在弹出菜单中，选择 **Map tools（地图工具）** 。

![添加地图](https://i.loli.net/2018/09/01/5b8a9234101c7.png)

在弹出菜单中，选择 **创建地图** 。

![添加地图](https://i.loli.net/2018/09/01/5b8a923409372.png)


此时进入区域选择界面，在地图上点击，以选择需要下载的区域的 **左上** 、 **右下** 顶点。形成的矩形范围，即为需要预先下载的离线地图的范围。选择完成后，点击底部的 **√（确认）** 按钮以确认范围。

![添加地图](https://i.loli.net/2018/09/01/5b8a92349af3c.png)

在弹出界面中，勾选地图图层粒度。数字越大，粒度越细，地图细节越好，需要下载的图片也就越多。一般下载到 **15~16** 级即可。然后输入地图名称，即可开始下载。

![添加地图](https://i.loli.net/2018/09/01/5b8a92340e867.png)


根据选择的图层粒度与区域大小，下载将持续一段时间。

![添加地图](https://i.loli.net/2018/09/01/5b8a92340b87d.png)

![添加地图](https://i.loli.net/2018/09/01/5b8a92340cf7c.png)

下载完成后，即会成功创建一个新的地图。退出创建地图界面，进入 **切换地图** 界面，选择 **OFFLINE** ，点击顶部的 **刷新** 按钮，即可看到刚刚创建的Goole Earth离线地图。需要使用时，切换到该地图即可。

![添加地图](https://i.loli.net/2018/09/01/5b8a9234135c2.png)

> 注：需要删除时，在地图列表长按希望删除的地图，即可将其删除。

---

### 使用3D地图

在下载了Google Earth卫星地图后，我们有时还需要查看地形信息，我们可以通过下载DEM文件，获取高度信息，通过OruxMaps的3D地图功能查看地形信息。

点击右上角的 **地图** 按钮，在弹出菜单中，选择 **Map tools（地图工具）** 。

![使用3D地图](https://i.loli.net/2018/09/01/5b8a923411d33.png)

在弹出的菜单中，选择 **3D地图** 。

![使用3D地图](https://i.loli.net/2018/09/01/5b8a92340348c.png)

如果此处没有用于保存高度信息的DEM文件，OruxMaps会提示你下载，点击 **确定** 以下载。

![使用3D地图](https://i.loli.net/2018/09/01/5b8a92afa7de4.png)

![使用3D地图](https://i.loli.net/2018/09/01/5b8a92af86c33.png)

下载完成后，即可在3D地图界面中查看地形信息。

![使用3D地图](https://i.loli.net/2018/09/01/5b8a92afc8eb2.png)

---

## 航迹

OruxMaps App的另一项实用功能，是支持记录行进的GPS航迹，在有价值的地方标记路点。在野外调查中，通过记录GPS航迹，在后期整理数据的时候，可以很方便地在Google Earth上查看当时的周边地形，亦可为相机的照片标记地理位置。本节主要介绍以下航迹功能：

- 记录GPS航迹
- 标记路点
- 查看航迹信息
- 合并/导出航迹
- 从数据文件载入航迹

### 记录GPS航迹

#### 开始记录GPS航迹

点击App顶部菜单的 **轨迹** 按钮。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a92afac5c2.png)

在弹出菜单中，选择 **开始记录** 选项，开始记录后，此选项会变成 **停止记录** 。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a92af7ea80.png)

开始记录后，界面底部出现 *“航迹记录中”* 提示，下方弹出航迹参数面板，且当前位置出现一个 **起点路点** 。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a92afb4a4f.png)

在航迹记录状态下，当位置发生移动后，移动的航迹将被记录，并在地图中以 *红色箭头* 表示。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a92afbe3b1.png)

#### 停止记录GPS航迹

当到达目的地，希望结束当前航迹记录时，点击 **轨迹** 菜单中的 **停止记录** 选项，即可停止记录航迹。

在弹出的界面中，检查填写航迹信息，点击右上角的 **√（确认）** 按钮保存。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a92afa46da.png)

保存后，会自动创建一个 **终点路点** ，并且其描述中，会附上本段航迹的运动信息。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a92afa630b.png)

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a92afb11c7.png)

#### 开始记录新的GPS航段

当已载入GPS航迹的时候，重新开始GPS航迹记录，会弹出选项，让用户选择是开始 **新航段** ，还是 **新航迹** 。

若认为新航迹与老航迹应当同属于一个航迹（如中午吃饭时，停止航迹记录，下午出发时，继续开始航迹记录，且两个航迹应当皆属于同一个航迹）则新的航迹应当被建立成一个新航段。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a93271c59a.png)

开始记录后，界面底部出现 *“继续记录轨迹，已开始的新航段”* 提示，下方弹出航迹参数面板，且当前位置出现另一个 **起点路点** 。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a93274c267.png)

此时航迹记录继续开始，当位置发生移动后，移动的航迹将被记录，并在地图中以 *红色箭头* 表示。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a9327503ef.png)

停止记录后，将能继续编辑当前航迹信息。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a932744998.png)

每当一个航段停止记录后，也将自动创建一个新的 **终点路点** ，并且其描述中，会附上本段航迹的运动信息。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a9327414a7.png)

多端航迹也将显示在同一屏幕中。

![记录GPS航迹](https://i.loli.net/2018/09/01/5b8a932755fab.png)

---

### 标记路点

#### 添加普通路点：

点击App顶部菜单的 **路点** 按钮。

![标记路点](https://i.loli.net/2018/09/01/5b8a932750ba3.png)

在弹出菜单中，选择 **创建** 选项。

![标记路点](https://i.loli.net/2018/09/01/5b8a93271addd.png)

在弹出的窗口中，填写路点的基本信息，点击右上角的 **√（确认）** 按钮保存。

![标记路点](https://i.loli.net/2018/09/01/5b8a93271a55f.png)

保存后，刚刚编辑的路点即会出现在地图上。

![标记路点](https://i.loli.net/2018/09/01/5b8a93274fb18.png)

#### 添加照片路点：

点击App顶部菜单的 **路点** 按钮，在弹出菜单中，选择 **照片路点** 选项。

![标记路点](https://i.loli.net/2018/09/01/5b8a93b508df3.png)

OruxMaps将调起系统相机，拍照后确认，在弹出的窗口中，填写路点的基本信息，点击右上角的 **√（确认）** 按钮保存，即可以该照片创建照片路点。

![标记路点](https://i.loli.net/2018/09/01/5b8a93b5035ce.png)

#### 查看路点信息：

点击页面上已有的路点，可以查看路点信息。进而可以进行 **编辑** 、 **删除** 等操作。

![标记路点](https://i.loli.net/2018/09/01/5b8a93b50b2b9.png)

#### 在地图任意位置标记路点：

拖动地图，将光标移动到希望标记路点的位置。

![标记路点](https://i.loli.net/2018/09/01/5b8a93b53dd55.png)

长按希望标记路点的位置，在弹出菜单中，选择 **创建路点** 。

![标记路点](https://i.loli.net/2018/09/01/5b8a93b506316.png)

在弹出的窗口中，填写路点的基本信息，点击右上角的 **√（确认）** 按钮保存。

![标记路点](https://i.loli.net/2018/09/01/5b8a93b504c17.png)

将光标移动到地图位置，可以测量当前位置与光标位置的 **距离** 、 **角度** 、 **直线到达时间** 等信息。

![标记路点](https://i.loli.net/2018/09/01/5b8a93b53a749.png)

---

### 查看航迹统计信息

在保存航迹后，我们可以管理并查看航迹的详情。

点击App顶部菜单的 **航迹/路径** 按钮。

![查看航迹统计信息](https://i.loli.net/2018/09/01/5b8a93b536095.png)

在弹出菜单中，选择 **Manage Track/Routes（管理航迹/路径）** 选项。

![查看航迹统计信息](https://i.loli.net/2018/09/01/5b8a93b501fc0.png)

进入航迹管理界面，在此可以进行查看航迹详情，合并、删除航迹等操作。

点击希望查看详情的航迹，在弹出的菜单中，选择 **Properties（属性）** 选项。

![查看航迹统计信息](https://i.loli.net/2018/09/01/5b8a93b5078a2.png)

在航迹属性界面中，点击 **查看航迹统计信息** 按钮。

![查看航迹统计信息](https://i.loli.net/2018/09/02/5b8b4e187038e.png)

此时即可查看当前航迹的信息。

![查看航迹统计信息](https://i.loli.net/2018/09/02/5b8b4e187428f.png)

点击右上角的 **配置（齿轮图标）** 按钮，可以选择具体查看哪个航段的信息。

![查看航迹统计信息](https://i.loli.net/2018/09/02/5b8b4e186aa08.png)

点击 **详细** 按钮，可以展开查看路径中各个距离阶段的 **时间** 、 **速度** 、 **高程** 等信息。

![查看航迹统计信息](https://i.loli.net/2018/09/02/5b8b4e1875fca.png)

点击 **查看图表** 按钮，可以查看 **时间**-**高程**/**速度**/**坡度**/**心跳次数**（*仅当有设备支持的情况下*） 图表。

![查看航迹统计信息](https://i.loli.net/2018/09/02/5b8b4e186f550.png)

图表的横轴为 **时间** ，纵轴为选定的参数的函数图像，航迹中的路点也将被标记出来。

![查看航迹统计信息](https://i.loli.net/2018/09/02/5b8b4e186a4ab.png)

---

### 合并航迹

已经记录保存的多个航迹，也可以作为航段，合并成一个新航迹。

点击App顶部菜单的 **航迹/路径** 按钮，在弹出菜单中，选择 **Manage Track/Routes（管理航迹/路径）** 选项，进入航迹管理界面。

勾选希望合并的航迹，选择 **合并航迹** 按钮。

![合并航迹](https://i.loli.net/2018/09/02/5b8b4e1864172.png)

![合并航迹](https://i.loli.net/2018/09/02/5b8b4e184819d.png)

合并后，即会生成一个新航迹。

![合并航迹](https://i.loli.net/2018/09/02/5b8b4e1869f1b.png)

---

### 导出航迹

#### 保存航迹

当调查结束后，通常需要把OruxMaps记录的航迹，导出成航迹文件，以查看编辑，或分享给他人。

点击App顶部菜单的 **航迹/路径** 按钮，在弹出菜单中，选择 **Manage Track/Routes（管理航迹/路径）** 选项，进入航迹管理界面。

勾选希望保存成航迹文件的航迹，选择 **保存航迹** 按钮。

![导出航迹](https://i.loli.net/2018/09/02/5b8b4e1863a9e.png)

在弹出的菜单中，选择希望保存的文件格式。

> **常用文件格式：**
> - GPX：可导入各种软件（如Lightroom等）的通用GPS航迹文件格式；
> - KML/KMZ：可导入GoogleEarth的GPS航迹文件格式；

![导出航迹](https://i.loli.net/2018/09/02/5b8b4e734a0b7.png)

选择后，即可将航迹以选择的文件格式保存至手机中。

#### 分享航迹

航迹亦可在直接保存后，分享至其他设备，以免去再从手机复制出来的麻烦。

点击App顶部菜单的 **航迹/路径** 按钮，在弹出菜单中，选择 **Manage Track/Routes（管理航迹/路径）** 选项，进入航迹管理界面。

点击希望分享的航迹，在弹出的菜单中，选择 **Properties（属性）** 选项。

在航迹属性界面中，点击 **分享航迹** 按钮。

![导出航迹](https://i.loli.net/2018/09/02/5b8b4e73746fd.png)

选择希望分享的航迹格式后，便会调起系统分享浮层，选择希望的分享方式即可。

![导出航迹](https://i.loli.net/2018/09/02/5b8b4e734b82d.png)

此处以`MIUI8`分享到 *小米云盘* 为例。

![导出航迹](https://i.loli.net/2018/09/02/5b8b4e734890f.png)

---

### 从数据文件载入航迹

我们可以将进行野外调查前，事先准备好的航迹/路点文件，导入OruxMap，以在野外调查时比对查看。

点击App顶部菜单的 **航迹/路径** 按钮，在弹出菜单中，选择 **Track/Routes tools（航迹/路径工具）** 选项。

![从数据文件载入航迹](https://i.loli.net/2018/09/02/5b8b4e7345af4.png)

在弹出菜单中，选择 **载入 KML/GPX 格式文件** 。

![从数据文件载入航迹](https://i.loli.net/2018/09/02/5b8b4e734738f.png)

在手机中选择希望载入的数据文件，即可载入文件。文件载入后，会弹出导航和记录选项窗口，功能如下：

- 导航：以载入的航迹文件为基准，开始导航。
- 记录：开启一个新的航迹记录。

![从数据文件载入航迹](https://i.loli.net/2018/09/02/5b8b4e7372a45.png)

载入后，航迹文件中的航迹、路点信息都将呈现在地图之中。

![从数据文件载入航迹](https://i.loli.net/2018/09/02/5b8b4e7383c95.png)