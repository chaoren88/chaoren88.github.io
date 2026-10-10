
<style>
  .spila-page {
    width: 100%;
    min-width: 0;
    text-align: center;
    overflow-wrap: anywhere;
  }

  .spila-page .spila-title,
  .spila-page .spila-intro {
    color: #4a708b;
  }

  .spila-page .spila-title {
    margin-top: 0;
    font-size: clamp(1.75rem, 4vw, 2.5rem);
    line-height: 1.2;
  }

  .spila-page .spila-intro {
    margin-inline: auto;
    max-width: 75ch;
  }

  .spila-page .image-container {
    display: grid;
    gap: clamp(10px, 2vw, 20px);
    width: 100%;
    margin-bottom: clamp(10px, 2vw, 20px);
  }

  .spila-page .image-container--three {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  .spila-page .image-container--two {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .spila-page .lab-image {
    display: block;
    width: 100%;
    max-width: 100%;
    aspect-ratio: 4 / 3;
    object-fit: cover;
    border-radius: 10px;
  }

  .spila-page .team-container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: clamp(12px, 3vw, 20px) 0;
  }

  .spila-page h2 {
    margin: 0 0 20px;
    font-size: clamp(1.5rem, 3vw, 2rem);
    line-height: 1.25;
  }

  .spila-page .students {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(min(100%, 160px), 1fr));
    gap: 32px 20px;
    align-items: start;
    margin-bottom: clamp(40px, 7vw, 60px);
  }

  .spila-page .student {
    min-width: 0;
    text-align: center;
  }

  .spila-page .student img {
    display: block;
    width: 120px;
    height: 120px;
    max-width: 100%;
    margin: 0 auto 10px;
    border-radius: 50%;
    object-fit: cover;
    object-position: center top;
  }

  .spila-page .student-name {
    font-size: 1.1rem;
    font-weight: 700;
  }

  .spila-page .student-name a {
    color: inherit;
    text-decoration: none;
  }

  .spila-page .student-name a:focus-visible {
    outline: 2px solid #4a708b;
    outline-offset: 3px;
  }

  .spila-page .student-role {
    color: #555;
    font-size: 1rem;
  }

  .spila-page .student-research {
    color: #777;
    font-size: 0.9rem;
  }

  .spila-page .student-work {
    margin-top: 10px;
    color: #444;
    font-size: 0.9rem;
  }

  @media (max-width: 640px) {
    .spila-page .image-container--three,
    .spila-page .image-container--two {
      grid-template-columns: 1fr;
    }

    .spila-page .students {
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 28px 12px;
    }

    .spila-page .student img {
      width: 104px;
      height: 104px;
    }
  }

  @media (max-width: 340px) {
    .spila-page .students {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="spila-page">
  <h1 class="spila-title">Welcome to our Super Pixel Intelligence LAB (SPILA)!</h1>

  <p class="spila-intro">We are interested in Image/Video Processing, Computer Vision, Artificial Intelligence, and Multimedia Communications and Information Systems, etc.</p>

  <div class="image-container image-container--three">
    <img src="/images/labs/lab-1.webp" alt="SPILA group activity" class="lab-image">
    <img src="/images/labs/icon.webp" alt="SPILA logo" class="lab-image">
    <img src="/images/labs/lab-2.webp" alt="SPILA group activity" class="lab-image">
  </div>

  <div class="image-container image-container--two">
    <img src="/images/labs/lab-2023.webp" alt="SPILA team in 2023" class="lab-image">
    <img src="/images/labs/lab-2025-2.webp" alt="SPILA team in 2025" class="lab-image">
  </div>

  <hr>

  <div class="team-container">
        <h2>PhD Students</h2>
        <div class="students">
            <div class="student">
                <img src="/images/labs/dkj.webp" alt="Xiaofeng Wang">
                <div class="student-name">Kejun Di (迪珂君)</div>
                <div class="student-role">PhD@SCU, 2026 - present</div>
                <div class="student-research">Image Restoration</div>
            </div>
            <div class="student">
                <img src="/images/labs/tzy.webp" alt="Xiaofeng Wang">
                <div class="student-name">Ziyi Tian (田子溢)</div>
                <div class="student-role">PhD@SCU, 2026 - present</div>
                <div class="student-research">Image Restoration</div>
            </div>
            <div class="student">
                <img src="/images/labs/xls.webp" alt="Xiaofeng Wang">
                <div class="student-name">Linsong Xiao (肖林松)</div>
                <div class="student-role">PhD@SCU, 2026 - present</div>
                <div class="student-research">Image Restoration</div>
            </div>
            <div class="student">
                <img src="/images/labs/liuxiao.webp" alt="Xiao Liu">
                <div class="student-name">
                    <a href="https://liuxiao.email/" target="_blank">Xiao Liu (刘晓)</a>
                </div>
                <div class="student-role">PhD@SCU, 2024 - present</div>
                <div class="student-research">Image Restoration</div>
            </div>
            <div class="student">
                <img src="/images/labs/wxf.webp" alt="Xiaofeng Wang">
                <div class="student-name">Xiaofeng Wang (王晓峰)</div>
                <div class="student-role">PhD@SCU, 2025 - present</div>
                <div class="student-research">Image Restoration</div>
            </div>
            <div class="student">
                <img src="/images/labs/ggh.webp" alt="Guihuan Guo">
                <div class="student-name">Guihuan Guo (国桂环)</div>
                <div class="student-role">PhD@SCU, 2024 - present</div>
                <div class="student-research">Image Restoration/3D Vision</div>
            </div>
            <div class="student">
                <img src="/images/labs/lm.webp" alt="Meng Li">
                <div class="student-name">Meng Li (李梦)</div>
                <div class="student-role">PhD@SCU, 2024 - present</div>
                <div class="student-research">Image Restoration</div>
            </div>
            <div class="student">
                <img src="/images/labs/txp.webp" alt="XiangPeng Tian">
                <div class="student-name">XiangPeng Tian (田相鹏)</div>
                <div class="student-role">PhD@SCU, 2023 - present</div>
                <div class="student-research">Image Restoration</div>
            </div>
        </div>

        <h2>MS Students</h2>
        <div class="students">
            <div class="student">
                <img src="/images/labs/hh.webp" alt="Hao Hong">
                <div class="student-name">Hao Hong (洪豪)</div>
                <div class="student-role">MS@SCU, 2025 - present</div>
                <div class="student-research">Agent</div>
            </div>
            <div class="student">
                <img src="/images/labs/wyl.webp" alt="YuLin Wu">
                <div class="student-name">YuLin Wu (吴宇林)</div>
                <div class="student-role">MS@SCU, 2025 - present</div>
                <div class="student-research">Agent</div>
            </div>
            <div class="student">
                <img src="/images/labs/zyh.webp" alt="Yuhan Zhao">
                <div class="student-name">Yuhan Zhao (赵钰涵)</div>
                <div class="student-role">MS@SCU, 2025 - present</div>
                <div class="student-research">Agent</div>
            </div>
            <div class="student">
                <img src="/images/labs/lmy.webp" alt="Mingyang Li">
                <div class="student-name">Mingyang Li (李鸣阳)</div>
                <div class="student-role">MS@SCU, 2024 - present</div>
                <div class="student-research">Edge-side, Lightweight, Deployment</div>
            </div>
            <div class="student">
                <img src="/images/labs/lfj.webp" alt="Fajing Liu">
                <div class="student-name">Fajing Liu (刘发静)</div>
                <div class="student-role">MS@SCU, 2024 - present</div>
                <div class="student-research">Image De-hazing and De-clouding</div>
            </div>
            <div class="student">
                <img src="/images/labs/yz.webp" alt="Zheng Yang">
                <div class="student-name">Zheng Yang (杨郑)</div>
                <div class="student-role">MS@SCU, 2024 - present</div>
                <div class="student-research">Medical Image Analysis</div>
            </div>
            <div class="student">
                <img src="/images/labs/hyq.webp" alt="Yiqi Hu">
                <div class="student-name">Yiqi Hu (胡屹琪)</div>
                <div class="student-role">MS@SCU, 2024 - present</div>
                <div class="student-research">Image Registration and Fusion</div>
            </div>
        </div>

        <h2>Research Interns</h2>
        <div class="students">
            <div class="student">
                <img src="/images/labs/psr.webp" alt="Shurui Peng">
                <div class="student-name">Shurui Peng (彭书睿)</div>
                <div class="student-role">BS@SCU, 2023 - present</div>
                <div class="student-research">Image Restoration/3D Vision</div>
            </div>
            <div class="student">
                <img src="/images/labs/hyx.webp" alt="Yuxin Hu">
                <div class="student-name">Yuxin Hu (胡雨馨)</div>
                <div class="student-role">BS@SCU, 2023 - present</div>
                <div class="student-research">Image Restoration/3D Vision</div>
            </div>
            <div class="student">
                <img src="/images/labs/ojc.webp" alt="jincen Ou">
                <div class="student-name">jincen Ou (欧津岑)</div>
                <div class="student-role">BS@SCU, 2023 - present</div>
                <div class="student-research">Image Restoration/3D Vision</div>
            </div>
        </div>        

        <h2>Graduates</h2>
        <div class="students">
            <div class="student">
                <img src="/images/labs/zth.webp" alt="Tianheng Zheng">
                <div class="student-name">Tianheng Zheng (郑天衡)</div>
                <div class="student-role">MS@SCU, 2023 - 2026</div>
                <div class="student-research">Image Registration and Fusion</div>
                <div class="student-work">MEGVII</div>
            </div>
            <div class="student">
                <img src="/images/labs/dgl.webp" alt="Guanglu Dong">
                <div class="student-name">Guanglu Dong (董广陆)</div>
                <div class="student-role">MS@SCU, 2023 - 2026</div>
                <div class="student-research">Image Deraining and Quality Assessment</div>
                <div class="student-work">KUAISHOU</div>
            </div>
            <div class="student">
                <img src="/images/labs/wsy.webp" alt="Shouyi Wang">
                <div class="student-name">Shouyi Wang (王守一)</div>
                <div class="student-role">MS@SCU, 2023 - 2026</div>
                <div class="student-research">Image Super-Resolution</div>
                <div class="student-work">ZTE</div>
            </div>
            <div class="student">
                <img src="/images/labs/zjy.webp" alt="Jiayu Zhong">
                <div class="student-name">Jiayu Zhong (钟嘉宇)</div>
                <div class="student-role">MS@SCU, 2023 - 2026</div>
                <div class="student-research">Few-shot Object Detection</div>
                <div class="student-work">SGCC</div>
            </div>
            <div class="student">
                <img src="/images/labs/ls.webp" alt="Shi Luo">
                <div class="student-name">Shi Luo (罗十)</div>
                <div class="student-role">BS@SCU, 2022 - 2026</div>
                <div class="student-research">Image Restoration/3D Vision</div>
                <div class="student-work">PhD student at ZJU</div>
            </div>
            <div class="student"> 
                <img src="/images/labs/nyt.webp" alt="Yuting Nie">
                <div class="student-name">Yuting Nie (聂玉婷)</div>
                <div class="student-role">BS@SCU, 2022 - 2026</div>
                <div class="student-research">Image Super-Resolution and Quality Assessment</div>
                <div class="student-work">Master student at SEU</div>
            </div>
            <div class="student">
                <img src="/images/labs/linxin.webp" alt="Xin Lin">
                <div class="student-name">
                    <a href="https://linxin0.github.io/" target="_blank">Xin Lin (林鑫)</a>
                </div>
                <div class="student-role">BS@SCU, 2021 - 2025</div>
                <div class="student-research">Image Restoration/3D Vision</div>
                <div class="student-work">PhD student at UCSD</div>
            </div>
            <div class="student">
                <img src="/images/labs/yjt.webp" alt="Jingtong Yue">
                <div class="student-name">
                    <a href="https://jingtong0527.github.io/" target="_blank">Jingtong Yue (岳靖童)</a>
                </div>
                <div class="student-role">BS@SCU, 2021 - 2025</div>
                <div class="student-research">Image Restoration/3D Vision</div>
                <div class="student-work">Master student at CMU</div>
            </div>
            <div class="student">
                <img src="/images/labs/sxy-2.webp" alt="Xiuya Shi">
                <div class="student-name">Xiuya Shi (石秀雅)</div>
                <div class="student-role">MS@SCU, 2022 - 2025</div>
                <div class="student-research">Image Restoration</div>
                <div class="student-work">SinopecGroup</div>
            </div>
            <div class="student">
                <img src="/images/labs/clf.webp" alt="Lufei Chen">
                <div class="student-name">Lufei Chen (陈卢飞)</div>
                <div class="student-role">MS@SCU, 2022 - 2025</div>
                <div class="student-research">Image Deblurring</div>
                <div class="student-work">Dji</div>
            </div>
            <div class="student">
                <img src="/images/labs/lxy.webp" alt="Xiangyu Liao">
                <div class="student-name">Xiangyu Liao (廖祥宇)</div>
                <div class="student-role">MS@SCU, 2022 - 2025</div>
                <div class="student-research">Image Denoising</div>
                <div class="student-work">OPPO</div>
            </div>
            <div class="student">
                <img src="/images/labs/hj.webp" alt="Jie Huang">
                <div class="student-name">Jie Huang (黄杰)</div>
                <div class="student-role">MS@SCU, 2021 - 2024</div>
                <div class="student-research">Image Denoising</div>
                <div class="student-work">CATL</div>
            </div>
        </div>        

  </div>
</div>

