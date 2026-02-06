# zhougroup_website


```html
<!doctype html> <!-- 声明：这是 HTML5 文档（浏览器用它来正确解析页面） -->
<html lang="en"> <!-- 网页最外层标签；lang="en" 表示页面主要语言是英文（有助于搜索/无障碍） -->

<head> <!-- head：放“页面信息”和“资源链接”，不会直接显示在页面内容里 -->
  <meta charset="UTF-8"> <!-- 字符编码：UTF-8（支持中文/英文/各种符号，最常用） -->
  <meta name="viewport" content="width=device-width, initial-scale=1"> <!-- 让手机/平板按设备宽度显示，缩放比例为 1 -->
  <title>Welcome to Prof. Tong Zhou's Research Group</title> <!-- 浏览器标签页标题 -->
  <link rel="stylesheet" href="css/style.css"> <!-- 引入 CSS 样式文件：用来控制页面的颜色、布局、字体等 -->
</head>

<body> <!-- body：网页真正“显示出来”的内容都写在这里 -->

  <header class="site-header"> <!-- 页头区域（通常放导航栏、Logo 等）；class 用于 CSS 选中它并设置样式 -->
    <div class="top-accent" aria-hidden="true"></div> <!-- 顶部装饰条；aria-hidden 表示给屏幕阅读器“忽略它”（纯装饰） -->

    <nav class="site-nav" aria-label="Primary"> <!-- nav：导航栏区域；aria-label 给无障碍工具一个说明 -->
      <a class="logo logo--eit" href="https://www.eitech.edu.cn/"> <!-- a：链接；点击后去 EIT 官网；class 表示这是一个 logo 链接 -->
        <img src="image/base/eit.png" width="340" alt="EIT"> <!-- img：图片；src 图片路径；width 宽度；alt 备用文字（图片加载失败或无障碍） -->
      </a>

      <ul class="nav-list"> <!-- ul：无序列表（导航菜单通常用列表做） -->
        <li class="nav-item nav-item--active"><a href="index.html">Home</a></li> <!-- li：列表项；active 表示当前页面（Home）高亮 -->
        <li class="nav-item"><a href="news.html">News</a></li> <!-- 链接到 News 页面 -->
        <li class="nav-item"><a href="research.html">Research</a></li> <!-- 链接到 Research 页面 -->
        <li class="nav-item"><a href="publications.html">Publications</a></li> <!-- 链接到 Publications 页面 -->
        <li class="nav-item"><a href="people.html">People</a></li> <!-- 链接到 People 页面 -->
        <li class="nav-item"><a href="photos.html">Photos</a></li> <!-- 链接到 Photos 页面 -->
        <li class="nav-item"><a href="lab.html">Lab</a></li> <!-- 链接到 Lab 页面 -->
        <li class="nav-item"><a href="teaching.html">Teaching</a></li> <!-- 链接到 Teaching 页面 -->
      </ul>

      <a class="logo logo--lab" href="index.html"> <!-- 右侧实验室 Logo，点击回到首页 -->
        <img src="image/base/logo3.png" width="340" height="70" alt="Jiang Lab"> <!-- 实验室 Logo 图片 -->
      </a>
    </nav> <!-- 导航栏结束 -->
  </header> <!-- 页头结束 -->

  <main> <!-- main：页面主体内容区域（语义化标签，利于 SEO/无障碍） -->

    <section class="hero" aria-label="Lab highlights"> <!-- section：一块内容区域；hero 常表示顶部大图区域 -->
      <div id="indeximg1" class="TopPhoto">
        <img src="image/fontphoto2.jpg" width="1300" height="300" alt="Lab highlight image 1">
      </div> <!-- 第一张轮播图（默认显示，因为没有 is-hidden） -->

      <div id="indeximg2" class="TopPhoto is-hidden">
        <img src="image/homemade%20STM%203.jpg" width="1300" height="300" alt="Lab highlight image 2">
      </div> <!-- 第二张轮播图（is-hidden 表示先隐藏） -->

      <div id="indeximg3" class="TopPhoto is-hidden">
        <img src="image/fontphoto3.jpg" width="1300" height="300" alt="Lab highlight image 3">
      </div> <!-- 第三张轮播图（隐藏） -->

      <div id="indeximg4" class="TopPhoto is-hidden">
        <img src="image/fontphoto2.jpg" width="1300" height="300" alt="Lab highlight image 4">
      </div> <!-- 第四张轮播图（隐藏） -->

      <div id="indeximg5" class="TopPhoto is-hidden">
        <img src="image/homemade%20STM%203.jpg" width="1300" height="300" alt="Lab highlight image 5">
      </div> <!-- 第五张轮播图（隐藏） -->

      <div id="indeximg6" class="TopPhoto is-hidden">
        <img src="image/fontphoto3.jpg" width="1300" height="300" alt="Lab highlight image 6">
      </div> <!-- 第六张轮播图（隐藏） -->

      <div id="indeximg7" class="TopPhoto is-hidden">
        <img src="image/fontphoto2.jpg" width="1300" height="300" alt="Lab highlight image 7">
      </div> <!-- 第七张轮播图（隐藏） -->

      <div id="indeximg8" class="TopPhoto is-hidden">
        <img src="image/homemade%20STM%203.jpg" width="1300" height="300" alt="Lab highlight image 8">
      </div> <!-- 第八张轮播图（隐藏） -->
    </section> <!-- 顶部轮播图区域结束 -->

    <section class="Show" aria-label="About the lab"> <!-- “关于实验室”区域 -->
      <div class="photo-card"> <!-- 左边的照片卡片容器 -->
        <img src="image/6f7c62116d604b6edecd41f12728c68.png" width="175" height="250" alt="Principal investigator portrait">
        <!-- 负责人/PI 的照片 -->
      </div>

      <div class="intro-card"> <!-- 右边介绍文字的卡片容器 -->
        <div class="intro-content"> <!-- 里面放具体标题和段落 -->
          <div class="section-title"> <!-- 一个小标题区域 -->
            <span class="title-text">Our Laboratory</span> <!-- 标题文字 -->
            <a href="research.html" class="more-link">more</a> <!-- “more” 链接到 research 页面 -->
          </div>

          <p class="body-text">
            Welcome to Prof. Tong Zhou’s research group in the College of Science at Eastern Institute of Technology, Ningbo. We explore condensed matter physics with an emphasis on topological quantum computation, topological quantum states, and quantum transport phenomena at superconductor-semiconductor interfaces.
          </p> <!-- 实验室简介正文段落 -->

          <p class="subheading">Research Interests</p> <!-- 小标题：研究兴趣 -->

          <p class="body-text">
            1. Topological quantum computing: platforms and strategies toward Majorana fusion and braiding.<br>
            2. Topological quantum states in insulators, semimetals, and superconductors under external fields.<br>
            3. Quantum transport at superconductor-semiconductor interfaces (Andreev reflection, Josephson effects, superconducting diode effects).<br>
            4. Quantum materials: novel electronic structure, superconductivity, magnetoelectricity, optics, and transport.<br>
            5. Micromagnetic simulations of topological magnetic textures and their coupling to electronic states.<br>
            6. Machine learning for discovery and prediction across the above directions.
          </p>
          <!-- 研究方向列表；<br> 表示换行（让每条单独一行显示） -->
        </div>
      </div>
    </section> <!-- 关于实验室区域结束 -->

    <section class="dierbankuai" aria-label="Highlights and news"> <!-- 第二个大模块：亮点 + 新闻 -->
      <div class="lastestnew"> <!-- 左侧：Highlights 区域容器 -->
        <div class="section-title section-title--wide"> <!-- 标题区域；--wide 可能表示更宽的样式 -->
          <span class="title-text">Highlights</span> <!-- 标题文字 -->
          <a href="publications.html" class="more-link">more</a> <!-- more 链接到 publications -->
        </div>

        <article class="highlight-card"> <!-- 一条亮点文章卡片（第 1 条） -->
          <img src="image/highlight/science.ado1544-f1.jpg" width="240" height="160" alt="Water transport study cover" class="highlight-image">
          <!-- 亮点文章的配图 -->
          <div class="highlight-text"> <!-- 右侧文字区域 -->
            <h3 class="highlight-title">Probing structural superlubricity of two-dimensional water transport with atomic resolution</h3>
            <!-- 亮点标题 -->
            <p class="body-text">
              Low-dimensional water transport can be drastically enhanced under atomic-scale confinement. However, its microscopic origin is still under debate. In this work, we directly imaged the atomic structure and transport of two-dimensional water islands on graphene and hexagonal boron nitride surfaces using qPlus-based atomic force microscopy...&nbsp;
              <!-- 亮点简介正文；&nbsp; 表示一个“不会被折叠的空格” -->
              <a href="https://www.science.org/doi/10.1126/science.ado1544" class="link"><span class="italic">Science</span> (2024).</a>
              <!-- 期刊链接 -->
              <a href="https://mp.weixin.qq.com/s/oLYn5vdk6wZd6ldSublJfA" class="link"><span class="italic">PKUPhy news</span></a>.
              <!-- 微信推文链接 -->
            </p>
          </div>
        </article>

        <article class="highlight-card"> <!-- 第 2 条亮点 -->
          <img src="image/highlight/41586_2024_7427_Fig1_HTML.webp" width="240" height="160" alt="Ice surface structure" class="highlight-image">
          <div class="highlight-text">
            <h3 class="highlight-title">Imaging surface structure and premelting of ice Ih with atomic resolution</h3>
            <p class="body-text">
              Ice surfaces are closely relevant to many physical and chemical properties, such as melting, freezing, friction, gas uptake and atmospheric reaction. Despite extensive experimental and theoretical investigations, the exact atomic structures of ice interfaces remain elusive owing to the vulnerable hydrogen-bonding network and the complicated premelting process...&nbsp;
              <a href="https://www.nature.com/articles/s41586-024-07427-8" class="link"><span class="italic">Nature</span> (2024).</a>
              <a href="https://mp.weixin.qq.com/s/U9wFE2nQCAdNOFfDPRVAPQ" class="link"><span class="italic">PKUPhy news</span></a>.
            </p>
          </div>
        </article>

        <article class="highlight-card"> <!-- 第 3 条亮点 -->
          <img src="image/highlight/41565_2023_1550_Fig1_HTML.webp" width="240" height="160" alt="Alkali ion packing" class="highlight-image">
          <div class="highlight-text">
            <h3 class="highlight-title">Nanoscale one-dimensional close packing of interfacial alkali ions driven by water-mediated attraction</h3>
            <p class="body-text">
              The permeability and selectivity of biological and artificial ion channels correlate with the specific hydration structure of single ions. However, fundamental understanding of the effect of ion–ion interaction remains elusive. Here, via non-contact atomic force microscopy measurements...&nbsp;
              <a href="https://www.nature.com/articles/s41565-023-01550-9" class="link"><span class="italic">Nature Nanotechnology</span> (2023).</a>
              <a href="https://mp.weixin.qq.com/s/4st0Rsam8mN9nkTVFIYyxA" class="link"><span class="italic">PKUPhy news</span></a>.
            </p>
          </div>
        </article>

        <article class="highlight-card"> <!-- 第 4 条亮点 -->
          <img src="image/2022science.png" width="240" height="160" alt="Hydrated protons visualization" class="highlight-image">
          <div class="highlight-text">
            <h3 class="highlight-title">Visualizing Eigen/Zundel cations and their interconversion in monolayer water on metal surfaces</h3>
            <p class="body-text">
              Hydrated protons play a critical role in numerous physical and chemical processes. However, their atomic-level characterization remains experimentally challenging, especially for interfacial systems. Using qPlus-based atomic force microscopy and path integral molecular dynamics...&nbsp;
              <a href="https://www.science.org/doi/10.1126/science.abo0823" class="link"><span class="italic">Science</span> 377(6603) 315-319 (2022).</a>
              <a href="https://news.pku.edu.cn/jxky/73a71706ebb84590932ab69a48d79fa8.htm" class="link"><span class="italic">PKU news</span></a>,
              <a href="https://newsen.pku.edu.cn/news_events/news/research/12691.html" class="link"><span class="italic">PKU news(English version)</span></a>,
              <a href="https://www.scholarset.com/post/detail?fid=2516" class="link"><span class="italic">Zhishe News</span></a>.
            </p>
          </div>
        </article>
      </div> <!-- Highlights 左侧区域结束 -->

      <aside class="youbianxinwen" aria-label="Breaking news"> <!-- aside：侧边栏（右侧新闻滚动） -->
        <div class="NEWS111"> <!-- 右侧标题条 -->
          <span>Breaking News</span> <!-- 标题文字 -->
          <a href="news.html" class="more-link">more</a> <!-- more 链接到 news 页面 -->
        </div>

        <div id="B" class="xinwenlundong"> <!-- 右侧新闻滚动容器；id="B" 方便 JS 找到它并控制滚动 -->
          <div id="B1" class="box1"> <!-- 第一份内容：真实新闻列表 -->
            <ul> <!-- 新闻列表 -->
              <li><span class="date">2023.10 :</span>
                Prof. Jiang was selected for The New Cornerstone Investigator Program ("新基石研究员项目"). Congratulations!
              </li> <!-- 一条新闻：日期 + 内容 -->

              <li><span class="date">2022.10 :</span>
                Jiani Hong won the National Scholarship. Congratulations to Jiani!
              </li> <!-- 下一条新闻 -->

              <li><span class="date">2022.07 :</span>
                Congratulations！Our paper "Visualizing Eigen/Zundel cations and their interconversion in monolayer water on metal surfaces" was published on <a href="https://www.science.org/doi/10.1126/science.abo0823" class="link"><span class="italic">Science</span></a>. see <a href="https://news.pku.edu.cn/jxky/73a71706ebb84590932ab69a48d79fa8.htm" class="link"><span class="italic">pku news</span></a>, <a href="https://newsen.pku.edu.cn/news_events/news/research/12691.html" class="link"><span class="italic">pku news (English)</span></a>, <a href="https://www.scholarset.com/post/detail?fid=2516" class="link"><span class="italic">Zhishe News</span></a>
              </li> <!-- 这条新闻里有多个链接 -->

              <li><span class="date">2022.03 :</span>
                Jinbo Peng joined the Tsung-Dao Lee Institute, Shanghai Jiao Tong University as a tenure-track Associate Professor. Congratulations to Jinbo!
              </li>

              <li><span class="date">2021.12 :</span>
                Our proposed project titled "Investigation and manipulation of nuclear quantum effects in light-element systems"（“基于轻元素全量子化效应的物态调控研究”）was granted by National Key R&amp;D Program of China（“国家重点研发计划”）.
              </li> <!-- &amp; 是 HTML 的“转义”：表示 & 字符 -->

              <li><span class="date">2021.10 :</span>
                Our group were invited to exhibit our core technology on " the 13th Five-Year Plan" scientific and technological innovation achievement exhibition! see <a href="image/photo/1/b77688a49703900c4d1228f2cfd49d7.jpg" class="link"><span class="italic">photo</span></a>.
              </li>

              <li><span class="date">2021.05 :</span>
                Congratulations to Ke Bian! Our new review article "Scanning probe microscopy" was published by <a href="https://www.nature.com/articles/s43586-021-00033-2#citeas" class="link"><span class="italic">Nat Rev Methods Primers</span></a>, <a href="file/2021/NatRevMethodsPrimer2021_SPM.pdf" class="link"><span class="italic">PDF Download</span></a>, <a href="file/2021/NatRevMethodsPrimer2021_SPM_PrimeView.pdf" class="link"><span class="italic">Poster Download</span></a>.
              </li>

              <li><span class="date">2021.03 :</span>
                Prof. Jiang won the Achievement in Asia Award (AAA)，Robert T. Poe Prize ("亚洲成就奖") by the International Organization of Chinese Physicists and Astronomers. Congratulations! <a href="http://www.phy.pku.edu.cn/info/1182/6486.htm" class="link"><span class="italic">pku news</span></a>, <a href="http://newsen.pku.edu.cn/news_events/news/focus/10694.htm" class="link"><span class="italic">pku news(english edition)</span></a>, <a href="http://ocpaweb.org/home/page/2020-ocpa-awards-report" class="link"><span class="italic">OCPA</span></a>.
              </li>

              <li><span class="date">2020.10 :</span>
                Our joint work with Xiamen University entitled "Surface Coordination Layer Passivates Oxidation of Copper" was published by <a href="https://www.nature.com/articles/s41586-020-2783-x" class="link"><span class="italic">Nature</span></a>.
              </li>

              <li><span class="date">2020.9 :</span>
                Prof. Jiang received the "Zhongguancun Award to Outstanding Young Scientists"（“杰出青年中关村奖”） by Beijing government. <a href="https://icqm.pku.edu.cn/xwdt/zxxw/922632.htm" class="link"><span class="italic">link</span></a>.
              </li>

              <li><span class="date">2020.8 :</span>
                Prof. Jiang won the "Nishina Asia Award"（“仁科芳雄亚洲奖”） by Nishina Memorial Foundation. <a href="https://www.nishina-mf.or.jp/news_en/2020/08/23/the-2020-the-eighth-nishina-asia-award-is-awarded/" class="link"><span class="italic">link</span></a>.
              </li>

              <li><span class="date">2020.1 :</span>
                Our paper "Atomic imaging of the edge structure and growth of a two-dimensional hexagonal ice" was published by <a href="https://www.nature.com/articles/s41586-019-1853-4" class="link"><span class="italic">Nature</span></a>.
              </li>

              <li><span class="date">2019.11 :</span>
                Prof. Jiang was invited to World Laureates Association Forum and gave a talk to 65 World Laureates (including 44 Nobel Prize Laureates). Prof. Jiang is one of the selected 10 speakers out of 100 worldwide young scientists. <a href="http://www.360doc.com/content/19/1104/10/535749_870990982.shtml" class="link"><span class="italic">link1</span></a>,<a href="https://www.shobserver.com/zaker/html/185046.html" class="link"><span class="italic">link2</span></a>,<a href="https://baijiahao.baidu.com/s?id=1648789244196791509&wfr=spider&for=pc" class="link"><span class="italic">link3</span></a>,<a href="http://jianggroup.pku.edu.cn/images/group/20191106014900.jpg" class="link"><span class="italic">see photo</span></a>,<a href="http://jianggroup.pku.edu.cn/images/group/speech.mp4" class="link"><span class="italic">see video</span></a>.
              </li>

              <li><span class="date">2019.09 :</span>
                Prof. Jiang was elected as a Fellow of the American Physical Society. <a href="http://pkunews.pku.edu.cn/xwzh/b747445894fe4ec883ce35666d7446b0.htm" class="link"><span class="italic">pku news</span></a>, <a href="http://newsen.pku.edu.cn/news_events/news/focus/8851.htm" class="link"><span class="italic">pku news(english edition)</span></a>.
              </li>

              <li><span class="date">2019.06 :</span>
                Prof. Jiang recieved "China-Youth Science and Technology Award"（中国青年科技奖） <a href="http://www.phy.pku.edu.cn/news/news19/190629.xml" class="link"><span class="italic">link</span></a>.
              </li>

              <li><span class="date">2019.02 :</span>
                Our work on ion hydrate was selected as "2018 Top-ten Science Advances of China"（中国科学十大进展）. <a href="http://news.pku.edu.cn/xwzh/8cabae56f2944bd48c4f7f9aef91866b.htm" class="link"><span class="italic">pku news</span></a>.
              </li>

              <li><span class="date">2019.02 :</span>
                Prof. Jiang was awarded "The leading innovative talent in the science and technology（“万人计划”科技创新领军人才）" by Central Chinese Government. <a href="file/Ten-thousand%20Talents%20Program.pdf" class="link"><span class="italic">see attached file</span></a>.
              </li>

              <li><span class="date">2018.06 :</span>
                Jing Guo joined the College of Chemistry in Beijing Normal University as a full Professor.
              </li>

              <li><span class="date">2018.05 :</span>
                Our paper "The effect of hydration number on the interfacial transport of sodium ions" was published by <a href="https://www.nature.com/articles/s41586-018-0122-2" class="link"><span class="italic">Nature</span></a>.
              </li>

              <li><span class="date">2018.05 :</span>
                Professor Jiang wins the 2018 Tan Kah Kee Young Scientist Award(陈嘉庚青年科学奖). <a href="http://www.cas.cn/yw/201805/t20180531_4647988.shtml" class="link"><span class="italic">link</span></a>, <a href="http://pkunews.pku.edu.cn/xwzh/2018-05/31/content_303081.htm" class="link"><span class="italic">pku news</span></a>, <a href="http://newsen.pku.edu.cn/news_events/news/focus/7306.htm" class="link"><span class="italic">pku news(english edition)</span></a>.
              </li>

              <li><span class="date">2017.08 :</span>
                Prof. Jiang was granted the "National Science Fund for Distinguished Young Scholars"（“国家杰出青年科学基金”）. <a href="http://www.nsfc.gov.cn/publish/portal0/tab434/info69936.htm" class="link"><span class="italic">link</span></a>, <a href="http://pkunews.pku.edu.cn/xwzh/2017-10/12/content_299436.htm" class="link"><span class="italic">pku news</span></a>.
              </li>

              <li><span class="date">2017.01 :</span>
                Our work in the nuclear quantum effects of water is elected as one of Top 10 Progresses of Science and Technology of China in 2016（中国科学十大进展）. <a href="http://pkunews.pku.edu.cn/xwzh/2017-01/03/content_296425.htm" class="link"><span class="italic">pku news</span></a>.
              </li>

              <li><span class="date">2016.03 :</span>
                Our paper"Nuclear quantum effects of hydrogen bonds probed by tip-enhanced inelastic electron tunneling" was accepted by <a href="https://science.sciencemag.org/content/352/6283/321" class="link"><span class="italic">Science</span></a>.
              </li>
            </ul> <!-- 新闻列表结束 -->
          </div> <!-- B1：第一份新闻内容结束 -->

          <div id="B2" class="box2"></div> <!-- B2：第二份内容（JS 会复制 B1 到这里，用于“无缝滚动”） -->
        </div> <!-- 滚动容器 B 结束 -->
      </aside> <!-- 右侧新闻栏结束 -->
    </section> <!-- 第二大模块结束 -->
  </main> <!-- 主体结束 -->

  <footer class="dibu"> <!-- 页脚区域 -->
    <div class="bottom"> <!-- 页脚内容外层容器 -->
      <div class="bottomsite"> <!-- 页脚站点导航（三列链接） -->
        <div class="bottoms1"><a href="index.html">Home</a><br><a href="news.html">News</a><br><a href="research.html">Research</a></div>
        <!-- 第一列：Home/News/Research；<br> 换行 -->
        <div class="bottoms2"><a href="publications.html">Publications</a><br><a href="people.html">People</a><br><a href="photos.html">Photos</a></div>
        <!-- 第二列：Publications/People/Photos -->
        <div class="bottoms3"><a href="lab.html">Lab</a><br><a href="teaching.html">Teaching</a><br><a href="contact-us.html">Contact Us</a></div>
        <!-- 第三列：Lab/Teaching/Contact Us -->
      </div>

      <div class="shengming"> <!-- 声明信息（地址、版权等） -->
        <div class="shengming1">Jiang&nbsp;&nbsp;&nbsp;Lab</div> <!-- &nbsp; 是不换行空格，用来控制显示间距 -->
        <div class="shengming2">Address: W568, Physics Building of Peking University, No.209 Chengfu Road, Haidian District, Beijing, China<br>
          Postcode: 100871 &nbsp;|&nbsp; Tel: +86-10-62757177&nbsp; |&nbsp; E-mail: yjiang@pku.edu.cn</div>
        <!-- 地址信息；| 两边用 &nbsp; 加空格让排版更好看 -->
        <div class="shengming3">©Jiang Lab. All Rights Reserved</div> <!-- 版权信息 -->
      </div>
    </div>
  </footer> <!-- 页脚结束 -->

  <script> <!-- 第一段 JavaScript：控制顶部大图轮播（indeximg1~8） -->
    let sec = 1; // sec：当前显示第几张图（1~8）
    const indexTimer = setInterval(() => count(0), 4000); // 每 4000ms(4秒) 调一次 count(0)

    function count(myindex) { // count 函数：负责切换顶部轮播图
      if (myindex !== 0) { // 如果传进来的参数不是 0（说明你想手动跳转到某张）
        sec = myindex; // 就把 sec 改成那张图的编号
      }

      for (let k = 1; k <= 8; k += 1) { // 循环 k=1 到 8
        const el = document.getElementById(`indeximg${k}`); // 找到 id 为 indeximg1/indeximg2/... 的元素
        if (el) { // 如果找到了这个元素（避免报错）
          el.classList.add('is-hidden'); // 给它加上 is-hidden 类（让它隐藏）
        }
      }

      const current = document.getElementById(`indeximg${sec}`); // 找到当前应该显示的那张
      if (current) { // 如果存在
        current.classList.remove('is-hidden'); // 移除 is-hidden（让它显示）
      }

      if (sec < 8) { // 如果还没到第 8 张
        sec += 1; // 下一次就显示下一张
      } else { // 如果已经是第 8 张了
        sec = 1; // 下一次回到第 1 张
      }
    }
  </script>

  <script> <!-- 第二段 JavaScript：控制另一个轮播（indimg1~8） -->
    let second = 1; // second：第二个轮播当前显示第几张（1~8）
    const highlightTimer = setInterval(() => count2(0), 2500); // 每 2.5 秒切一次

    function count2(myind) { // count2：切换第二个轮播图
      if (myind !== 0) { // 如果传入了指定编号
        second = myind; // 直接跳到该编号
      }

      for (let k = 1; k <= 8; k += 1) { // 循环 1~8
        const el = document.getElementById(`indimg${k}`); // 找到 indimg1/2/...
        if (el) { // 如果找到元素
          el.classList.add('is-hidden'); // 全部先隐藏
        }
      }

      const current = document.getElementById(`indimg${second}`); // 找到要显示的那张
      if (current) { // 如果存在
        current.classList.remove('is-hidden'); // 显示它
      }

      if (second < 8) { // 如果没到最后
        second += 1; // 下一张
      } else { // 如果到最后
        second = 1; // 回到第一张
      }
    }
  </script>

  <script> <!-- 第三段 JavaScript：控制右侧 Breaking News 自动向上滚动 -->
    const speed = 50; // 滚动速度：数值越小滚动越快（这里每 50ms 滚动一次）
    const B = document.getElementById('B'); // 拿到滚动容器（外层）
    const B1 = document.getElementById('B1'); // 第一份新闻内容
    const B2 = document.getElementById('B2'); // 第二份内容（用来复制，制造无缝循环）

    if (B && B1 && B2) { // 确保三个元素都存在，否则不执行（避免报错）
      B2.innerHTML = B1.innerHTML; // 把 B1 的内容复制一份到 B2（这样滚到底还能接着滚）
      B.scrollTop = 0; // 把滚动条位置设为顶部

      function marquee() { // marquee：每次调用都让滚动条往下（内容往上）移动一点点
        if (B.scrollTop >= B1.scrollHeight) { // 如果已经滚到超过 B1 的高度
          B.scrollTop = 0; // 就瞬间回到顶部（实现循环滚动）
        } else { // 否则
          B.scrollTop += 1; // 每次向下滚动 1 像素（内容看起来向上移动）
        }
      }

      let myMar = setInterval(marquee, speed); // 按 speed 定时执行 marquee（开始自动滚动）

      B.addEventListener('mouseover', () => clearInterval(myMar)); // 鼠标放上去就暂停滚动
      B.addEventListener('mouseout', () => { // 鼠标移开就继续滚动
        myMar = setInterval(marquee, speed); // 重新开始定时器
      });
    }
  </script>

</body> <!-- 页面显示内容结束 -->
</html> <!-- 整个 HTML 文档结束 -->

```