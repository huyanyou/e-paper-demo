<template>
  <div>
    <div id="top">
      <img src="../assets/logo.png" alt="logo">
      <span id="top-title">墨水屏群控管理演示</span>
    </div>
    <div>
      <div class="spacing">
      </div>
      <div id="content">
        <table border="0" width="100%" cellpadding="0px">
          <tr>
            <th align="left">屏幕型号</th>
            <th align="left">设备IP</th>
            <th align="left">设备MAC</th>
            <th align="left">SSID</th>
            <th align="left">信号强度</th>
            <th align="left">电池电量</th>
            <th align="left">模板编号</th>
            <th align="left">显示内容</th>
            <th align="left">内容状态</th>
            <th align="left" style="width:10%">上传时间</th>
            <th align="left" style="width:10%">最后上线时间</th>
            <th align="left" style="width:15%">操作</th>
          </tr>
          <tr>
            <td>E-ink 75b</td>
            <td>192.168.1.3</td>
            <td>a0:78:17:7d:76:e0</td>
            <td>singzer</td>
            <td>-75db</td>
            <td>68%</td>
            <td>01</td>
            <td>测试会议</td>
            <td>已上传</td>
            <td>2022/3/23 16:36:18</td>
            <td>2022/3/23 16:36:18</td>
            <td>
              <span>编辑</span>
              <span>编辑</span>
              <span>编辑</span>
            </td>
          </tr>
          <tr>
            <td>E-ink 75b</td>
            <td>192.168.1.3</td>
            <td>a0:78:17:7d:76:e0</td>
            <td>singzer</td>
            <td>-75db</td>
            <td>68%</td>
            <td>01</td>
            <td>测试会议</td>
            <td>等待设备唤醒</td>
            <td>2022/3/23 16:36:18</td>
            <td>2022/3/23 16:36:18</td>
            <td>
              <span>编辑</span>
              <span>编辑</span>
              <span>编辑</span>
            </td>
          </tr>
        </table>
        <div id="content-btn">
          <button>批量编辑内容</button>
          <button>批量上传</button>
        </div>
      </div>
      <div class="spacing">

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  img {
    height: 8rem;
    width: 8rem;
    border-radius: 50%;
    margin-left: 6rem;
  }

  table {
    margin-left: 5rem;
    margin-right: 5rem;
  }

  th {
    font-size: 3rem;
    color: #90939F;
  }

  td {
    font-size: 3rem;
    color: black;
    height: 6rem;
  }

  tr:not(:first-child):hover {
    background-color: #F5F5F5;
  }

  #top {
    background-color: #409EEF;
    height: 10rem;
  }

  #content-btn{
    float: right;
    margin-top: 2rem;
  }

  button {
    background-color: #409EEF;
    color: white;
    border: none;
    border-radius: 5px;
    /* height: 4rem; */
    /* width: 8rem; */
    /* margin-left: 1rem;
    margin-right: 1rem; */
    padding: 1rem 3rem;
    font-size: 3rem;
  }

  button:first-child{
    margin-right: 5rem;
  }

  button:not(:first-child) {
    margin-right: 18rem;
  }

  .spacing{
    height: 5rem;
    background-color: #F5F7FA;
    width: 100%;
  }
  .spacing:nth-child(3){
    position: absolute;
    bottom: 0;
  }
  #top-title {
    color: #FFFFFF;
    font-size: 4rem;
    margin-left: 6rem;
    position: relative;
    top: -2rem;
  }
</style>
