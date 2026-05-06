<template>
  <div>
    <header class="nav">
      <div class="container nav-inner">
        <div class="brand">Mengfei <b>/ Frontend Engineer</b></div>
        <nav class="nav-links">
          <a href="#about">关于</a>
          <a href="#skills">技能</a>
          <a href="#featured">项目</a>
          <a href="#experience">经历</a>
          <a href="#contact">联系</a>
        </nav>
      </div>
    </header>

    <main>
      <section class="hero">
        <div class="container hero-grid reveal">
          <article class="panel hero-main">
            <div class="eyebrow">Enterprise Frontend Engineer · 3 Years of Experience</div>
            <h1 class="hero-title">李梦飞<span class="accent">.</span></h1>
            <div class="hero-subtitle">专注 Vue 生态、实时数据可视化与企业级业务系统交付</div>
            <p class="hero-summary">
              我长期参与能源管理、智慧园区、物联网平台、可视化大屏、H5 与后台系统建设。
              擅长在复杂 B 端场景中处理实时数据、图表展示、性能优化与可维护性问题，持续交付稳定、清晰且具备业务价值的前端方案。
            </p>
            <div class="hero-actions">
              <a class="btn btn-primary" href="#featured">查看精选项目</a>
              <a class="btn btn-ghost" href="mailto:1351468279@qq.com">联系我</a>
            </div>
            <div class="hero-metrics">
              <div class="metric"><div class="num">3年</div><div class="txt">持续参与真实企业项目开发与交付</div></div>
              <div class="metric"><div class="num">7+</div><div class="txt">覆盖能源、物联网、后台与 H5 等项目场景</div></div>
              <div class="metric"><div class="num">Vue 双栈</div><div class="txt">具备 Vue2 / Vue3 企业级落地经验</div></div>
            </div>
          </article>

          <aside class="panel hero-side">
            <div class="identity-card">
              <div class="identity-top">
                <div class="avatar">LM</div>
                <div>
                  <div class="identity-name">李梦飞</div>
                  <div class="identity-role">Frontend Engineer / 企业级前端开发工程师</div>
                </div>
              </div>
              <div class="meta-grid">
                <div class="meta"><div class="k">求职方向</div><div class="v">前端开发工程师</div></div>
                <div class="meta"><div class="k">期望城市</div><div class="v">南京</div></div>
                <div class="meta"><div class="k">邮箱</div><div class="v">1351468279@qq.com</div></div>
                <div class="meta"><div class="k">教育背景</div><div class="v">本科 · 数字媒体技术</div></div>
              </div>
            </div>
            <div class="tag-group">
              <span class="tag">Vue 2 / Vue 3</span>
              <span class="tag">TypeScript</span>
              <span class="tag">ECharts</span>
              <span class="tag">WebSocket / MQTT</span>
              <span class="tag">B 端平台</span>
              <span class="tag">数据可视化</span>
              <span class="tag">工业互联网</span>
            </div>
          </aside>
        </div>
      </section>

      <section id="about">
        <div class="container grid-2">
          <div class="panel content-panel reveal">
            <div class="section-head">
              <div>
                <h2 class="section-title">关于我</h2>
                <p class="section-desc">我更关心的不是单个页面，而是复杂业务如何被高质量地落到产品里。</p>
              </div>
            </div>
            <p class="section-desc" style="margin-top: 0">
              我主要面向企业级前端项目，长期参与能源管理、工业互联网、智慧园区、可视化大屏与后台管理系统开发，熟悉需求理解、界面实现、前后端协作、组件封装、性能优化以及项目交付流程。
            </p>
            <p class="section-desc">
              在具体实践中，我更擅长处理实时数据通信、复杂列表渲染、动态图表展示、动态路由与权限场景，并将工程化思维落到代码结构、复用能力与长期维护上。
            </p>
          </div>
          <div class="panel content-panel reveal" id="skills">
            <div class="section-head">
              <div>
                <h2 class="section-title">能力模型</h2>
                <p class="section-desc">围绕业务理解、工程实现、性能优化与体验质量建立自己的工作方式。</p>
              </div>
            </div>
            <div class="ability-grid">
              <div class="ability"><h3>业务理解</h3><p>能够快速理解 B 端平台、设备管理、监控调度等业务结构，并转化为清晰的前端实现方案。</p></div>
              <div class="ability"><h3>工程实现</h3><p>熟悉 Vue 生态开发模式，能够完成组件化、模块化、路由与状态管理设计。</p></div>
              <div class="ability"><h3>性能优化</h3><p>具备实时数据、海量列表、超万点图表等高复杂场景的优化经验。</p></div>
              <div class="ability"><h3>交互体验</h3><p>能够根据设计稿高质量还原界面，并兼顾操作效率、页面流畅度与可维护性。</p></div>
            </div>
          </div>
        </div>
      </section>

      <section>
        <div class="container grid-2">
          <div class="panel content-panel reveal">
            <div class="section-head">
              <div>
                <h2 class="section-title">技能矩阵</h2>
                <p class="section-desc">以 Vue 生态为主，覆盖可视化、实时通信、工程化与多端开发。</p>
              </div>
            </div>
            <div class="skills-matrix">
              <div class="skill-row"><h3>基础能力</h3><div class="chips"><span class="chip">HTML5</span><span class="chip">CSS3</span><span class="chip">JavaScript</span><span class="chip">TypeScript</span></div></div>
              <div class="skill-row"><h3>Vue 生态</h3><div class="chips"><span class="chip">Vue 2</span><span class="chip">Vue 3</span><span class="chip">Vue Router</span><span class="chip">Pinia</span><span class="chip">Vuex</span><span class="chip">Axios</span></div></div>
              <div class="skill-row"><h3>可视化与通信</h3><div class="chips"><span class="chip">ECharts</span><span class="chip">WebSocket</span><span class="chip">MQTT</span><span class="chip">Socket.io</span></div></div>
              <div class="skill-row"><h3>工程化与多端</h3><div class="chips"><span class="chip">Webpack</span><span class="chip">Vite</span><span class="chip">组件封装</span><span class="chip">动态路由</span><span class="chip">RBAC 权限</span><span class="chip">uni-app</span><span class="chip">H5</span></div></div>
            </div>
          </div>
          <div class="panel content-panel reveal">
            <div class="section-head">
              <div>
                <h2 class="section-title">项目场景</h2>
                <p class="section-desc">这些场景定义了我当前最有辨识度的专业方向。</p>
              </div>
            </div>
            <div class="scene-grid">
              <div class="scene"><h4>能源监控平台</h4><p>面向光伏、风电、储能、充电站等电力站点的实时监控与调度。</p></div>
              <div class="scene"><h4>工业互联网</h4><p>设备接入、子设备管理、数据采集与消息监控。</p></div>
              <div class="scene"><h4>可视化大屏</h4><p>图表、地图、看板与业务指标实时展示。</p></div>
              <div class="scene"><h4>后台管理系统</h4><p>权限控制、动态路由、业务配置与模块化开发。</p></div>
              <div class="scene"><h4>智慧园区</h4><p>面向工业园区与充储一体化场景的数据管理与监控。</p></div>
              <div class="scene"><h4>安装监管平台</h4><p>现场监控、风险隐患、录像追溯与跨系统通信。</p></div>
              <div class="scene"><h4>H5 应用</h4><p>移动端业务应用、首屏优化与组件化开发。</p></div>
              <div class="scene"><h4>多端协作</h4><p>支持 iframe、独立页面、后台系统与可嵌入式模块。</p></div>
            </div>
          </div>
        </div>
      </section>

      <section id="featured">
        <div class="container">
          <div class="section-head reveal">
            <div>
              <h2 class="section-title">精选项目</h2>
              <p class="section-desc">以下三个项目最能体现我在复杂业务场景中的前端实现能力。</p>
            </div>
          </div>

          <div class="featured-grid">
            <article class="project reveal">
              <div class="project-head">
                <div>
                  <h3>能源管理与监控平台</h3>
                  <div class="positioning">面向分布式电站的 B 端实时监控与调度平台</div>
                </div>
                <div class="time">2025.12 - 2026.01</div>
              </div>
              <div class="project-grid-inner">
                <div>
                  <p><strong>核心职责：</strong>负责实时数据接入、大屏图表渲染、海量列表性能优化与状态管理设计。</p>
                  <p><strong>技术亮点：</strong>基于 MQTT 订阅电站主题，服务层采用缓冲队列 + 100ms 批处理写入 Pinia；图表使用 ECharts 渲染功率曲线与仪表盘，并对超万点序列使用 LTTB 降采样；通过自研虚拟滚动支撑万级电站与告警列表展示。</p>
                  <p><strong>结果价值：</strong>在高频数据更新场景中平衡实时性、流畅度与可维护性，支撑更复杂的监控页面交付。</p>
                  <div class="stack"><span>Vue 3</span><span>Pinia</span><span>Element Plus</span><span>ECharts</span><span>WebSocket</span><span>MQTT</span></div>
                </div>
                <aside class="mini-board">
                  <h4>项目价值</h4>
                  <div class="mini-stat">
                    <div><b>实时性：</b>支持高频电站数据接入与状态展示</div>
                    <div><b>性能：</b>兼顾大屏图表与万级列表渲染压力</div>
                    <div><b>稳定性：</b>实现断线重连与连接状态反馈</div>
                  </div>
                </aside>
              </div>
            </article>

            <article class="project reveal">
              <div class="project-head">
                <div>
                  <h3>电力物联网平台</h3>
                  <div class="positioning">面向设备接入、应用管控与数据采集的物联网业务平台</div>
                </div>
                <div class="time">2025.10 - 2025.11</div>
              </div>
              <div class="project-grid-inner">
                <div>
                  <p><strong>核心职责：</strong>负责实时消息通信模块、设备消息监控界面和大体量消息展示优化。</p>
                  <p><strong>技术亮点：</strong>通过 WebSocket 与后端网关进行实时消息通信，支撑应用生命周期管理、子设备管理和控制命令下发；使用虚拟列表对超大量消息进行优化展示。</p>
                  <p><strong>结果价值：</strong>体现了我在设备接入型平台、实时消息流与性能优化方面的持续实践经验。</p>
                  <div class="stack"><span>Vue 2</span><span>Vue Router 3</span><span>Vuex 3</span><span>Element UI</span><span>Axios</span><span>WebSocket</span></div>
                </div>
                <aside class="mini-board">
                  <h4>项目关键词</h4>
                  <div class="mini-stat">
                    <div><b>设备管理：</b>面向子设备与应用生命周期</div>
                    <div><b>实时通信：</b>WebSocket 消息交互与监控</div>
                    <div><b>可扩展：</b>适合平台型业务模块持续扩展</div>
                  </div>
                </aside>
              </div>
            </article>

            <article class="project reveal">
              <div class="project-head">
                <div>
                  <h3>68宠物 H5 & 后台管理系统</h3>
                  <div class="positioning">覆盖移动端业务与 PC 后台管理的双端系统</div>
                </div>
                <div class="time">2024.03 - 2024.08</div>
              </div>
              <div class="project-grid-inner">
                <div>
                  <p><strong>核心职责：</strong>负责 H5 与后台系统功能开发、权限控制、组件复用与性能优化。</p>
                  <p><strong>技术亮点：</strong>H5 端采用 Vant 组件库、路由懒加载与 GZIP 压缩，使首屏加载时间降低 30%；后台系统实现 RBAC 权限控制、Excel 批量导入导出以及高复用业务组件封装。</p>
                  <p><strong>结果价值：</strong>说明我不仅能做大屏和平台，也具备业务后台、移动端和实际交付场景的综合开发能力。</p>
                  <div class="stack"><span>Vue 3</span><span>TypeScript</span><span>Pinia</span><span>Socket.io</span><span>Element Plus</span><span>Vant</span></div>
                </div>
                <aside class="mini-board">
                  <h4>业务价值</h4>
                  <div class="mini-stat">
                    <div><b>首屏优化：</b>移动端加载体验更快</div>
                    <div><b>管理能力：</b>RBAC 与导入导出提升后台效率</div>
                    <div><b>复用建设：</b>沉淀高复用组件与业务模块</div>
                  </div>
                </aside>
              </div>
            </article>
          </div>
        </div>
      </section>

      <section>
        <div class="container">
          <div class="section-head reveal">
            <div>
              <h2 class="section-title">其他项目</h2>
              <p class="section-desc">补充展示我的项目覆盖面与行业连续性。</p>
            </div>
          </div>
          <div class="simple-projects reveal">
            <div class="simple-item"><h4>新能源电力系统框架</h4><p>基于若依 Vue2 基建构建动态路由框架，支持第三方公司页面无缝接入，实现菜单动态生成与性能优化。</p></div>
            <div class="simple-item"><h4>智慧安装管理云平台</h4><p>通过 postMessage 与主框架通信，支持 iframe 嵌入与独立访问，并集成实时视频播放能力。</p></div>
            <div class="simple-item"><h4>智慧园区项目</h4><p>实现发电、负荷、充放电与功率等曲线和排名展示，支持多级筛选与近实时监控。</p></div>
            <div class="simple-item"><h4>工商储可视化大屏</h4><p>开发内网电力数据大屏，集成图表与地图展示电站实时数据，并结合 GeoJSON 处理完成地图可视化。</p></div>
          </div>
        </div>
      </section>

      <section id="experience">
        <div class="container grid-2">
          <div class="panel content-panel reveal">
            <div class="section-head">
              <div>
                <h2 class="section-title">工作经历</h2>
                <p class="section-desc">在两家公司持续积累企业级项目交付经验。</p>
              </div>
            </div>
            <div class="timeline">
              <article class="timeline-item">
                <div class="timeline-top">
                  <div>
                    <div class="timeline-title">前端开发工程师</div>
                    <div class="timeline-company">南京金航信息技术有限公司</div>
                  </div>
                  <div class="time">2024.08 - 2026.02</div>
                </div>
                <p>参与能源监控、智慧园区、物联网平台与安装管理系统等多个企业级项目开发，负责核心页面实现、数据交互、实时通信、图表展示与性能优化，推动前端模块稳定落地。</p>
              </article>
              <article class="timeline-item">
                <div class="timeline-top">
                  <div>
                    <div class="timeline-title">前端开发</div>
                    <div class="timeline-company">河南知更鸟信息技术有限责任公司</div>
                  </div>
                  <div class="time">2023.07 - 2024.07</div>
                </div>
                <p>负责前端界面开发与维护，完成视觉稿还原、业务后台模块实现、前后端联调与页面性能优化，积累了组件化开发与工程化实践经验。</p>
              </article>
            </div>
          </div>

          <div class="panel content-panel reveal">
            <div class="section-head">
              <div>
                <h2 class="section-title">教育背景</h2>
                <p class="section-desc">数字媒体技术背景，为前端开发与交互理解提供了良好的基础。</p>
              </div>
            </div>
            <article class="timeline-item" style="background: rgba(255,255,255,.03); box-shadow:none;">
              <div class="timeline-top">
                <div>
                  <div class="timeline-title">河南牧业经济学院</div>
                  <div class="timeline-company">本科 · 数字媒体技术</div>
                </div>
                <div class="time">2019 - 2023</div>
              </div>
              <p>在学习期间形成了对视觉表达、数字内容与交互设计的理解，并在后续工作中逐步转向企业级前端方向持续深耕。</p>
            </article>
          </div>
        </div>
      </section>

      <section id="contact">
        <div class="container reveal">
          <div class="contact-card">
            <div class="contact-grid">
              <div>
                <h2>期待加入优秀团队</h2>
                <p>
                  我希望继续专注企业级前端方向，在更有挑战的业务场景中打造稳定、流畅且有业务价值的产品界面。
                  如果你的团队正在寻找一位具备 Vue 生态、可视化、实时通信与 B 端经验的前端工程师，欢迎联系我。
                </p>
              </div>
              <div class="contact-list">
                <div class="contact-item"><div class="k">邮箱</div><div class="v">1351468279@qq.com</div></div>
                <div class="contact-item"><div class="k">求职方向</div><div class="v">前端开发工程师</div></div>
                <div class="contact-item"><div class="k">期望城市</div><div class="v">南京</div></div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer class="footer container">© 2026 李梦飞 · Advanced Resume Website · Built with Vue 3 and Vite.</footer>
  </div>
</template>

<script setup>
import { onMounted } from 'vue'

onMounted(() => {
  const items = document.querySelectorAll('.reveal')
  const io = new IntersectionObserver(
    (entries) => {
      entries.forEach((entry) => {
        if (entry.isIntersecting) {
          entry.target.classList.add('in')
          io.unobserve(entry.target)
        }
      })
    },
    { threshold: 0.12 }
  )

  items.forEach((item) => io.observe(item))
})
</script>
