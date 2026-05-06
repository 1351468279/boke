<template>
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
</template>
