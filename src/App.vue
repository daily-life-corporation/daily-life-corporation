<template>
  <div id="app"> 
    <div id="wrapper" class="toggled">
      <div class="row header">
        <div class="col-2">
          <a onclick="menu_toggle()" class="btn" style="cursor: pointer;">
            <div class="menu-icon"></div>
            <div class="menu-icon"></div>
            <div class="menu-icon"></div>
          </a>
        </div>
        <div class="col-10" align="right">
          <div class="dropdown" style="cursor: pointer;">
            <img src="dist/img/logo2.png" class="avatar" />
            <button class="dropbtn">
              นายวรายุทธ เทกระโทก
              <i class="fa fa-caret-down"></i>
            </button>
            <div class="dropdown-content">
              <a class="dropdown-item" href=""><i class="fa fa-user"></i>Profile</a>
              <a class="dropdown-item" href=""><i class="fa fa-sign-out"></i>Log
                Out
              </a>
            </div>
          </div>
        </div>
      </div>
      <div id="sidebar-wrapper">
        <ul class="sidebar-nav">
          <li class="logo">
            <div align="center">
              <img src="dist/img/logo2.png" class="img-responsive" style=" padding-top: 10%;" width="170px">
            </div>
          </li>
          <li>
            <div style="padding: 20px 0; text-indent: 0px;" align="center">
              <span class="brand-line-one"></span><br>
              <a href="">
                <span class="brand-line-second"> DAILY LIFE CORPORATION</span><br>
              </a>
            </div>
          </li>
          <li>
            <a href="">
              <div>
                <i class="fab fa-typo3" style="font-size:24px"></i>
                <span style="padding:5px; font-size:15px; "> ประเภทผู้ใช้งาน </span>
              </div>
            </a>
          </li>
          <li>
            <a href="">
              <div>
                <i class="fas fa-user" style="font-size:24px"></i>
                <span style="padding:5px; font-size:15px;"> ผู้ใช้งาน </span>
              </div>
            </a>
          </li>
        </ul>
      </div>
      <div id="page-content-wrapper">
        <hello></hello>
      </div>
      <center>
        <footer>
          <p>&copy; 2019 - DEILY LIFE CORPORATION</p>
        </footer>
      </center>
    </div> 
  </div> 
</template> 
<script>
  import Hello from './components/Hello.vue' 
  export default {
    name: 'app',
    components: {
      Hello
    }
  }
</script>