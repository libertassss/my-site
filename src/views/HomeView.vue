<script setup lang="ts"></script>

<template>
  <main style="width: 100%">
    <div style="display: flex; width: 100%; justify-content: space-between">
      <div>
        <h1 text-3xl="" font-bold="" mb-2="">
          钟媛媛 <small style="font-style: italic; opacity: 0.5">Yuanuan.zhong</small>
        </h1>
        <div op80="" mb-2="" flex-center="">👨‍💻 前端开发工程师 工作经验： 5年</div>
        <p>
          📮<a target="_blank" href="mailto:2767389215@qq.com" underline="true">
            2767389215@qq.com
          </a>
          📱<a target="_blank" href="tel:13133838536">13133838536</a>
        </p>
        <p style="display: flex; justify-content: space-between">
          <span style="margin-right: 20px">教育背景：江西师范大学</span>
          <span style="margin-right: 20px">就读时间: 2014.09-2018.06</span>
          <span>所学专业：信息管理与信息系统</span>
        </p>
      </div>

      <span
        style="width: 100px; height: 100px; border-radius: 100%; overflow: hidden; display: block"
      >
        <img
          style="width: 100%"
          w-100px=""
          rounded-full=""
          mb-2=""
          md:float-right=""
          src="../assets/images/me.jpg"
          alt="Avatar"
        />
      </span>
    </div>
    <div class="h-1px"></div>
    <h2 style="margin-bottom: 10px">
      技术栈 <small style="font-style: italic; opacity: 0.5">Stacks</small>
    </h2>
    <p>
      使用 Vue / React / TypeScript / Webpack / Vite
      作为主要语言和技术栈，有flutter、微信小程序开发经验。
    </p>
    <h2 style="margin-top: 30px">
      工作经历 <small style="font-style: italic; opacity: 0.5">Works</small>
    </h2>
    <div style="font-size: 18px; display: flex; justify-content: space-between">
      <div>
        上海物盾信息科技有限公司 <span style="opacity: 0.7; font-size: 14px">前端工程师</span>
      </div>
      <small style="opacity: 0.5">2022.06-至今</small>
    </div>
    <ul style="margin-bottom: 30px">
      <li>
        <h3>
          EMS、EMU
          <small style="opacity: 0.6">(技术栈:vue3、typescript、vite、antv x6、antd-vue)</small>
        </h3>
        独立负责EMS、EMU前端开发, EMS为二级储能管理系统,EMU为一级。<br />
        1、EMS可管理多台储能设备,可对设备下发各种充放电以及保护策略、例如防逆流防过需、电池保护等<br />
        2、可设计电路架构,用antv x6图形引擎设计好的绘制电路架构。<br />
        3、规则引擎功能模块，可用配置一系列规则，后端求解后下发给设备执行，用来处理一些特殊情况
        4、SSE服务端推送用电实时数据
      </li>
      <li>
        <h3>
          物安盾平台
          <small style="opacity: 0.6"
            >(技术栈:react、typescript、webpack、qiankun、Echarts、papaparse)</small
          >
        </h3>
        该平台是由4个独立应用组成的。<br />
        1、主应用包涵登录、登出、多租户、人员管理、设备管理等功能模块 <br />
        2、零信任子应用包含组网相关模块、创建网络、绘制网络拓扑图、以及配置网络访问规则等 <br />
        3、配置工具子应用为以上EMS/EMU的一个工具应用，主要为了将不同厂家设备的协议转换成我们的标准协议。标准协议存在csv文件里，使用papaparse插件将scv转成json，在下拉框渲染出来给用户选择
      </li>
      <li>
        <h3>
          TSpider
          <small style="opacity: 0.6">(技术栈:flutter、window_manager)</small>
        </h3>
        独立负责TSpider的客户端开发。TSpider是一个vpn组网工具的gui程序,后端使用go。<br />
        1、主要功能模块有拉起go服务、登录、登出、切换企业、查看所有网络列表，以及每个网络下的设备和人员<br />
        2、使用SystemTray设置系统托盘<br />
        3、packges制作mac安装包，编写在安装过程中需要执行的脚本，安装时启动go服务，go去执行服务注册，之后就会开机自启动了，不需要客户端去拉起了。<br />
        4、innosetup制作windows安装包，由于不知道该工具如何在安装过程中使用脚本，所以windows端是在客户端中用powershell拉起go服务的
      </li>
      <li>
        <h3>
          电网相关历史项目
          <small style="opacity: 0.6">(技术栈:angular、webpack)</small>
        </h3>
        1、支持一些老旧项目的需求交付
      </li>
      <li>
        <h3>制定前端开发规范以及配置gitlab CI/CD</h3>
        1、和前端小伙伴共同制定前端开发规范、代码中安装git hook、eslint、prettierrc等约束<br />
        2、研究并配置gitlab CI/CD,安装gitlab runner,实现自动构建和部署<br />
        3、学习docker的简单实用
      </li>
    </ul>

    <div style="font-size: 18px; display: flex; justify-content: space-between">
      <div>百姓网 <span style="opacity: 0.7; font-size: 14px">前端工程师</span></div>
      <small style="opacity: 0.5">2021.03-2022.05</small>
    </div>
    <ul style="margin-bottom: 30px">
      <li>
        <h3>
          百姓网搜索通售卖系统标王2.0
          <small style="opacity: 0.6">(技术栈:vue全家桶)</small>
        </h3>
        1、负责该售卖系统（查价、购买、后台审核更改行业）前端全链路流程的开发<br />
        2、优化原有的公共组件，拆分代码数量过多的组件
      </li>
      <li>
        <h3>
          百姓网搜索通售卖系统标王加购
          <small style="opacity: 0.6">(技术栈:vue全家桶)</small>
        </h3>
        1、独立负责该项目的前端开发<br />
        2、与服务端约定商品数据结构，在没有商品管理的情况下（商品为非标商品，无法配置化），最大限度的实现商品可配置化，灵活应对销售侧的各种线上调整
      </li>
      <li>
        <h3>
          百姓网神盾项目（反爬虫）
          <small style="opacity: 0.6">(技术栈:vue2)</small>
        </h3>
        1、负责开发滑块验证码前端部分，适配了移动端和pc端<br />
        2、在店铺项目中接入，对所有访问ip进行拦截，弹出滑动验证页面，以保障当前访问ip不是爬虫
      </li>
      <li>
        <h3>日常迭代</h3>
        1、搜索通广告业务线各个投放产品的开发和维护<br />
        2、分类技术业务线个产品的迭代开发和维护，主要技术栈 react全家桶 + nestJs<br />
        3、带实习生，给实习生制定成长任务，合理分配开发任务 <br />
        4、参与内部前端联盟的学习活动，学习前端脚手架的原理，基于lerna开发多包单仓库形式的脚手架
      </li>
    </ul>
    <div style="font-size: 18px; display: flex; justify-content: space-between">
      <div>虎扑 <span style="opacity: 0.7; font-size: 14px">前端工程师</span></div>
      <small style="opacity: 0.5">2019.02-2021.03</small>
    </div>
    <ul style="margin-bottom: 30px">
      <li>
        <h3>虎扑⼩小英雄公益项⽬ <small style="opacity: 0.6">(技术栈:react全家桶)</small></h3>
        1、独立负责此项⽬的开发迭代⼯作，webpack+express搭建项⽬⼯程<br />
        2、使⽤html2canvas开发截图分享功能 3、使用css3编写收取积分的动画效果
      </li>
      <li>
        <h3>
          ⻁扑App基础服务迭代
          <small style="opacity: 0.6">(技术栈:react、vue全家桶、typescript、fis )</small>
        </h3>
        1、独立完成⾜球球员⻚改版重构，利⽤canvas进⾏雷达图的绘制，根据每个球员的不同数值渲染不同的雷达图
        用户满意度达90% <br />
        2、足球各榜单等其他app内嵌h5的开发 <br />
        3、维护⽼业务，战报等内嵌h5（Vue fis）<br />
        4、各种运营活动的开发，例如弹幕互动、地图点亮（高德地图）、答题、投票、疫情地图等 （react
        vue
        typescript），并整理输出活动⻚必备基础功能集合⽂档（站内外分享流程、图⽚站内外分享流程、站内打开链接规则整理以及拉新归因）<br />
        5、业务开发过程中，与客户端联调，排查bridge功能bug，推动客户端迭代优化，解决历史遗留问题<br />
        6、协助运维跨团队沟通梳理前端基础应⽤，将⽼旧应⽤接cicd发布，解决历史遗留问题 <br />
        7、负责各种运营工具管理后台开发，以及跨团队协助社区团队做商城管理后台开发 <br />
        8、参与公司内部编程马拉松⼤赛，负责前端展示⻚⾯的开发，利⽤canvas绘制动态词云、bizcharts进⾏图表绘制
        （react bizcharts），获得⼀等奖 <br />
      </li>
      <li>
        <h3>拓海项目</h3>
        1、小程序的维护 （wepy），其他tp、laraver框架项⽬维护 <br />
        2、参与cba官网的重构，负责⼤部分重构工作 <br />
        3、独⽴负责nfl会员俱乐部公众号网页的开发，实现微信授权登录，使⽤微信jsapi实现本地相册访问更换头像，pdf
        ⽂件预览和下载等（react typescript）<br />
        4、独立负责拜仁官⽹重构，⽤媒体查询和弹性布局实现响应式布局，⼀套代码适配移动端和pc端(react
        typescript)
      </li>
    </ul>
  </main>
</template>

<style lang="less" scoped>
.h-1px {
  width: 100%;
  height: 1px;
  background: #9ca3af4d;
  margin-top: 10px;
}
</style>
