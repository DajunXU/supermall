<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
	export default {
		name: "TabBar"
	}
</script>

<style scoped>
  /*#tab-bar {
    !* 本身的样式 *!
    background-color: #f6f6f6;
    height: 49px;
    border-top: 1px solid #eee;
    box-shadow: 0px -1px 1px rgba(150,150,150,.08);

    !* 定位相关 *!
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;

    !* 利用flex进行布局 *!
    display: flex;
    text-align: center;
  }*/
  #tab-bar{
    display: flex;
    background-color: #f6f6f6;
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    box-shadow: 0px -2px 1px rgba(100,100,100,.1);
  }
</style>


