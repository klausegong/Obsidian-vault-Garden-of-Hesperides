# Obsidian-vault-Garden-of-Hesperides
为科研而生的Obsidian库🎉，打造以“期刊-学者-机构-笔记”四为一体的笔记生态工作流
![image.png](https://klausepicgo.oss-cn-hangzhou.aliyuncs.com/img/202405192138022.png)
### 1 、为什么会做这个库
我原来使用的笔记软件是 wolai, 也曾接触过 notion，会与 ob 结缘是因为使用了青柠学术的 zotero one 插件，从 zotero 开始到 obsidian 的学术自动化工作流的接触，让我的科研效率有了很大幅度的进步，当时就在（小红书）科研推土机上写了一系列的推文记录我的学习过程，其中有一篇还被青柠学术放在了他们的用户故事中：
![image.png](https://klausepicgo.oss-cn-hangzhou.aliyuncs.com/img/202405192036804.png)


于是在这个基础上，我想着是否应该做一些合理的延伸与补充，因为大哥们只是在技术上给我提供了可能性，但是实际使用上我却发现了一个很关键的痛点，从 zotero 导入到 obsidian 的文献笔记虽然有双链功能，但是笔记的相关信息，例如学者还是需要进行创建的，如下图：
![image.png](https://klausepicgo.oss-cn-hangzhou.aliyuncs.com/img/202405190237654.png)


同样地，“期刊“和“科研机构”这两块也是需要自己进行创建的，那么我是否可以先进行提前的录入一大部分相关内容来提高我对于我对文献相关信息的快速了解，于是就有了进行这个库基础的配置思路，<font color="#9bbb59">==构建起一个以文献笔记为核心，“学者-期刊-机构“为辅的学术库==</font>，也就是你现在看到的这个 ==Garden of Hesperides== 库。
![image.png](https://klausepicgo.oss-cn-hangzhou.aliyuncs.com/img/202405190246168.png)

![image.png](https://klausepicgo.oss-cn-hangzhou.aliyuncs.com/img/202405191558301.png)

<br />

### 2、库名字的来由
中文版本：<br />
**赫斯珀里得斯花园**（Garden of Hesperides）它出自希腊神话中金苹果树所在的花园。这个花园被认为是位于世界的尽头，由海仙女守护着。金苹果代表着知识和智慧，因此赫斯珀里得斯花园象征着学术追求的最高境界。使用这个名称作为学术库的名称，寓意着这个库是一个珍贵的知识宝库，里面藏有丰富的学术资源，等待着学者和学生们去探索和发现。它暗示着学术库是一个神圣而美丽的地方，在那里人们可以获得启迪和灵感。

英文版本：<br />
**Garden of Hesperides** is a highly poetic name for an academic library. It is drawn from Greek mythology, referring to the garden where the golden apples grow. This garden is said to be located at the end of the world and guarded by nymphs. The golden apples represent knowledge and wisdom, which is why the Garden of Hesperides symbolizes the highest level of academic achievement. Using this name for an academic library suggests that the library is a precious storehouse of knowledge, containing a wealth of academic resources for scholars and students to explore and discover. It implies that the library is a sacred and beautiful space, where people can find inspiration and enlightenment. Furthermore, the name "The Garden of Hesperides" has international appeal, as it is a well-known reference from Greek mythology. It is suitable for all types of academic libraries, including research libraries and specialized libraries.

法语版本：<br />
**Le jardin des Hespérides**  est un nom de bibliothèque universitaire très poétique. Il est tiré de la mythologie grecque et désigne le jardin où se trouve l'arbre aux pommes d'or. Ce jardin est censé se trouver au bout du monde et être gardé par des nymphes marines. Les pommes d'or représentent la connaissance et la sagesse, c'est pourquoi le jardin des Hespérides symbolise le summum de la quête académique. Utiliser ce nom pour une bibliothèque universitaire suggère que celle-ci est un précieux trésor de connaissances, contenant de riches ressources académiques que les universitaires et les étudiants peuvent explorer et découvrir. Cela laisse entendre que la bibliothèque est un lieu sacré et magnifique, où les gens peuvent trouver l'inspiration et l'illumination. De plus, le nom "Le jardin des Hespérides" a une portée internationale, car il s'agit d'une référence mythologique grecque bien connue. Il convient à tous les types de bibliothèques universitaires, y compris les bibliothèques de recherche et les bibliothèques spécialisées.

### 3、 声明
(1) 本库使用的 Components 插件为收费插件（主要实现主页按钮以及快速搜索可视化功能），目前为早鸟内测阶段，仍能免费使用，如需购买可按开发者提供购买激活方式进行购买，目前开发者推出[早鸟价格](https://wxycbt0cjk.feishu.cn/docx/QigvddUTloAUf9xTRX5capy3nwG) ，同时 Components开发者也有推出相关[返利活动](https://wxycbt0cjk.feishu.cn/docx/TaySdtCqhox3ECxIj9ecWfminSb), 活动截止期限不祥。若选择不购买的用户，也可以自行将主页搜索按钮以及相关 markdown 可视化操作换成其他免费开源的 [dataview方案](https://zhuanlan.zhihu.com/p/409253101)，例如[宋爽博士的 papperbell 库的方案](https://github.com/SongshGeo/Obsidian-PaperBell)；<br />
(2）**本库在使用上全开源，除以上第一点提及的 component 插件外，在使用上不存在任何付费部分**，请放心使用；<br />
(3) 本库中所使用的图片皆为 demo 图片，用户可自行更改，如有侵权请联系，立即删除；<br />
(4) 共享的 Garden of Hesperides 库中所设置的期刊、机构和学者文件夹中仅包含示例 markdown, 用户可以按照教程通过模版自行添加。

<br />

### 4、加入微信讨论群
![image.png](https://klausepicgo.oss-cn-hangzhou.aliyuncs.com/img/202405210111539.png)

### 4、更多学术技能分享，小红书关注 [科研推土机](https://www.xiaohongshu.com/user/profile/5eb1007c000000000100613d)




