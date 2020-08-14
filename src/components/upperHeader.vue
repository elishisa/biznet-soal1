<template>
  <header style="top: 0; left: 0; z-index: 10;">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 col-5 name-instance text-right">
          <div class="logo-container-onboarding">
            <strong>NAME INSTANCE</strong>
          </div>
        </div>
      </div>
      <div class="row" style="margin-top: 10px;">
        <div class="col-lg-6 col-6">
          <div class="menubar">
            <a>SS2.1</a>
            &nbsp;
            <a>|</a>
            &nbsp;
            <a>2 GB RAM</a>
            &nbsp;
            <a>|</a>
            &nbsp;
            <a>1 vCPU</a>
            &nbsp;
            <a>|</a>
            &nbsp;
            <a>60 GB Disk</a>
            &nbsp;
            <a>|</a>
            &nbsp;
            <a>Ubuntu 18.04 LTS</a>
            &nbsp;
          </div>
        </div>
        <div class="col-lg-6 col-6 text-right bottom-delete">
          <button type="button" class="btn btn-outline-danger">DELETE</button>
        </div>
      </div>
      <div class="menubar-delete"></div>
      <div class="row" style="margin-top: 10px; margin-bottom:10px;">
        <div class="row col-lg-6 col-6">
          <div class="col-sm-6 menubar-powerstate">PowerState :</div>
          <div class="col-sm-6 menubar-running">
            <strong>Running</strong>
          </div>
        </div>
        <div class="col-lg-6 col-2 text-right">
          <img src="../assets/Power-Buttons.png" style="height: 20px; margin-right:-30px;" />
        </div>
      </div>
      <div class="menubar-delete"></div>
    </div>
  </header>
</template>
<script>
export default {};
</script>
<style>
.menubar-delete {
  border-bottom: solid 1px #e6eaee;
  margin-bottom: 10px;
}
.bottom-delete {
  margin-top: -20px;
  margin-bottom: 15px;
}
.logo-container-boarding {
  font-size: 20px;
  color: #2222;
}
.container {
  padding: 30px;
}
.menubar {
  font-size: 13px;
  color: #6c6c6c;
}
.menubar-powerstate {
  font-size: 14px;
  color: #6c6c6c;
}
.menubar-running {
  font-size: 14px;
  color: #01a19a;
  margin-left: -6rem;
}
button {
  margin-top: -20px;
}
.name-instance {
  margin-bottom: 5px;
}
</style>