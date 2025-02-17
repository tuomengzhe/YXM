<script setup>
import { ref } from 'vue'
</script>

<template>
  <div class="common-layout">
    <el-container class="container">
      <el-aside class="left-aside">
        <img class="logo-white" src="./assets/logo-white.png" alt="logo-white">
        <el-button class="left-btn top-btn" type="primary">
          <img src="./icons/landmark.svg" class="left-icon" alt="landmark">
          <span class="left-text">首页</span>
        </el-button>
        <el-button class="left-btn" type="primary">
          <img src="./icons/pen-to-square.svg" class="left-icon" alt="pen-to-square">
          <span class="left-text">提问</span>
        </el-button>
        <el-button class="left-btn" type="primary">
          <img src="./icons/pen-clip.svg" class="left-icon" alt="pen-clip">
          <span class="left-text">热门创作</span>
        </el-button>
        <el-button class="left-btn" type="primary">
          <img src="./icons/lightbulb.svg" class="left-icon" alt="lightbulb">
          <span class="left-text">热点资讯</span>
        </el-button>
        <img class="log-in" src="./icons/登录.svg" alt="log-in">
      </el-aside>
      <el-container class="right-container">
        <el-header class="header">
          <div class="head-area">
            <el-col>
              <img class="head-icon" src="./assets/logo-blue.png" alt="logo-blue">
            </el-col>
            <el-col class="head-text">
              <el-row class="uptext">研小梦</el-row>
              <el-row class="downtext">你的智能学习助手</el-row>
            </el-col>
          </div>
          <img class="right-log-in" src="./icons/请先登录.svg" alt="right-log-in">
        </el-header>
        <el-main class="right-main">
          <el-container class="ask">
            <el-header class="right-head">
              <img class="big-arrow" src="./icons/big-arrow.svg" alt="big-arrow">
              <span class="big-arrow-text">提问</span>
            </el-header>
            <el-main class="ask-main">
              <el-container class="ask-left">
                <input class="ask-input" type="text" placeholder="输入消息...">
                <div class="ask-info">

                </div>
                <div class="ask-foot">
                  <img src="./icons/image.svg" class="ask-icon1" alt="image">
                  <img src="./icons/paper-plane.svg" class="ask-icon2" alt="paper-plane">
                </div>
              </el-container>
              <el-container class="ask-right">
                <span class="ask-right-top">猜你想看</span>
                <div class="ask-right-head">
                  <span class="ask-right-text">建筑ai渲染新玩法上线啦~抢先<(￣︶￣)↗体验[GO!]</span>
                </div>
                <div class="ask-right-main">
                  <img class="ask-right-img" src="./assets/ai-img1.jpg" alt="ass-right-img">
                  <img class="ask-right-img" src="./assets/ai-img2.jpg" alt="ass-right-img">
                  <img class="ask-right-img" src="./assets/ai-img3.jpg" alt="ass-right-img">
                  <div class="ask-right-more">
                    <img class="ask-right-more-iocn" src="./icons/big-arrow.svg" alt="ask-right-more-iocn">
                    <div class="ask-right-more-text">查看更多</div>
                  </div>
                </div>
              </el-container>
            </el-main>
          </el-container>
          <el-container class="assistant">
            <el-header class="right-head">
              <img class="big-arrow" src="./icons/big-arrow.svg" alt="big-arrow">
              <span class="big-arrow-text">考研小助手</span>
            </el-header>
            <el-main class="assistant-main">
              <el-container class="assistant-left">
                <div class="asspart">
                  <div class="asspart-head">
                    <img class="small-arrow" src="./icons/small-arrow.svg" alt="small-arrow">
                    <span class="small-arrow-text">考研英语</span>
                  </div>
                  <div class="asspart-main">
                    <img class="ass-icon" src="./assets/language.png" alt="language">
                    <div class="ass-text">
                      <span class="ass-text-up">大家都在搜</span>
                      <span class="ass-text-down">考研英语翻译技巧<br>考研英语完形填空真题<br>......</span>
                    </div>
                  </div>
                </div>
                <div class="asspart">
                  <div class="asspart-head">
                    <img class="small-arrow" src="./icons/small-arrow.svg" alt="small-arrow">
                    <span class="small-arrow-text">考研政治</span>
                  </div>
                  <div class="asspart-main">
                    <img class="ass-icon" src="./assets/book1.png" alt="book1">
                    <div class="ass-text">
                      <span class="ass-text-up">大家都在搜</span>
                      <span class="ass-text-down">考研政治理论框架整理<br>考研政治命题预测<br>......</span>
                    </div>
                  </div>
                </div>
                <div class="asspart">
                  <div class="asspart-head">
                    <img class="small-arrow" src="./icons/small-arrow.svg" alt="small-arrow">
                    <span class="small-arrow-text">考研数学</span>
                  </div>
                  <div class="asspart-main">
                    <img class="ass-icon" src="./assets/book2.jpg" alt="book2">
                    <div class="ass-text">
                      <span class="ass-text-up">大家都在搜</span>
                      <span class="ass-text-down">考研数学考研冲刺班材料<br>考研数学历年真题解析<br>......</span>
                    </div>
                  </div>
                </div>
              </el-container>
              <img class="more-subject" src="./icons/更多学科.svg" alt="more-subject">
              <el-container class="assistant-right">
                <div class="ass-h">
                  <img class="small-arrow" src="./icons/small-arrow.svg" alt="small-arrow">
                  <span class="ass-arrow-text">个人学习资料上传</span>
                </div>
                <span class="ass-m">可以让AI更好的识别你的学习习惯哦</span>
                <div class="ass-b">
                  <div class="ass-left">
                    <div class="ass-left-in">
                      <div class="ass-left-text">
                        <input class="ass-input" type="text" placeholder="输入信息...">
                      </div>
                      <div class="ass-left-icon">
                        <img class="ass-left-icon1" src="./icons/file-pdf.svg" alt="ass-left-icon1">
                        <img class="ass-left-icon2" src="./icons/image.svg" alt="ass-left-icon2">
                        <img class="ass-left-icon3" src="./icons/paper-plane.svg" alt="ass-left-icon3">
                      </div>
                    </div>
                  </div>
                  <div class="ass-right">
                    <div class="ass-right-in">
                      <div class="ass-right-head">
                        <span class="ass-right-head-text">历史记录</span>
                      </div>
                      <div class="ass-right-main">
                        <div class="ass-right-bar">
                          <img class="ass-right-bar-icon" src="./icons/search.svg" alt="ass-right-bar-icon">
                          <div class="ass-right-bar-input">
                            <input class="ass-right-bar-input-content" type="text" placeholder="搜索">
                          </div>
                        </div>
                        <div class="ass-right-content">

                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </el-container>
            </el-main>
          </el-container>
          <el-container class="other">
            <el-header class="right-head">
              <img class="big-arrow" src="./icons/big-arrow.svg" alt="big-arrow">
              <span class="big-arrow-text">其他AI应用</span>
            </el-header>
            <el-main class="other-main">
              <div class="othpart">
                <img class="other-icon" src="./assets/A.jpg" alt="A">
                <div class="other-text">
                  <span class="other-text-up">豆包</span>
                  <span class="other-text-down">豆包是你的AI聊天智能对话问答助手，写作文案翻译情感陪伴编程全能工具。</span>
                </div>
              </div>
              <div class="othpart">
                <img class="other-icon" src="./assets/B.jpg" alt="B">
                <div class="other-text">
                  <span class="other-text-up">文心一言</span>
                  <span class="other-text-down">作为你的智能伙伴，我既能写文案、想点子，又能陪你聊天、答疑解惑。</span>
                </div>
              </div>
              <div class="othpart">
                <img class="other-icon" src="./assets/C.jpg" alt="C">
                <div class="other-text">
                  <span class="other-text-up">ChatGPT</span>
                  <span class="other-text-down">AI智能问答机器人 全新4.0技术，响应速度更快，多轮问答上下文回复，一键秒解疑难问题。</span>
                </div>
              </div>
              <div class="othpart">
                <div class="othpart-left">
                  <img class="othpart-left-icon" src="./icons/plus.svg" alt="othpart-left-icon">
                </div>
                <div class="othpart-right">
                  <span class="othpart-right-text">创建我的AI智能体</span>
                </div>
              </div>
            </el-main>
          </el-container>
        </el-main>
        <el-footer class="right-footer">
          <span class="footer-text">关于我们</span>
          <span class="footer-text">隐私政策</span>
          <span class="footer-text">用户协议</span>
          <span class="footer-text">联系我们</span>
          <span class="footer-text">官方网站: www.tmzjy.com</span>
        </el-footer>
      </el-container>
    </el-container>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background-color: #f1f6f9;
}

.more-subject {
  width: 80px;
  position: absolute;
  bottom: 250px;
  right: 670px;
}

.ask-right {
  background-color: white;
  height: 82%;
  flex: 0.4;
  border-radius: 30px;
  margin: 0 28px;
  display: flex;
  flex-direction: column;

  .ask-right-top {
    position: absolute;
    background: transparent;
    top: 135px;
    right: 580px;
    font-family: 'Microsoft Yahei';
    font-weight: bold;
    font-size: 10px;
  }

  .ask-right-head {
    flex: 0.3;
    background: transparent;

    .ask-right-text {
      height: 50px;
      color: #636363;
      background: transparent;
      font-family: 'Microsoft Yahei';
      font-size: 8px;
      margin-left: 40px;
      line-height: 50px;
    }
  }

  .ask-right-main {
    flex: 0.7;
    background: transparent;
    display: flex;
    flex-direction: row;

    .ask-right-img:first-child {
      object-fit: cover;
      height: 165px;
      width: 110px;
      border-radius: 15px;
      margin-left: 25px;
    }

    .ask-right-img:not(:first-child) {
      object-fit: cover;
      height: 165px;
      width: 110px;
      border-radius: 15px;
      margin-left: 18px;
    }

    .ask-right-more {
      height: 165px;
      width: 110px;
      background-color: #d4ddeb;
      border-radius: 15px;
      margin-left: 18px;
      margin-bottom: 25px;
      display: flex;
      flex-direction: row;
      align-items: center;

      .ask-right-more-iocn {
        background: transparent;
        width: 8px;
        margin-left: 25px;
      }

      .ask-right-more-text {
        background: transparent;
        font-family: 'Microsoft Yahei';
        font-size: 10px;
        font-weight: bolder;
        margin-left: 8px;
      }
    }
  }
}

.assistant-right {
  display: flex;
  flex-direction: column;

  .ass-h {
    background-color: white;
    margin-top: 7px;
    border-radius: 100px;
    display: flex;
    align-items: center;
    height: 10px;

    .ass-arrow-text {
      margin-left: 5px;
      background-color: white;
      font-family: 'Microsoft Yahei';
      font-weight: bold;
      font-size: 14px;
    }
  }

  .ass-m {
    background-color: white;
    margin: 6px 35px;
    font-family: 'Microsoft Yahei';
    font-size: 10px;
  }

  .ass-b {
    height: 70%;
    display: flex;
    flex-direction: row;
    background-color: white;

    .ass-left {
      height: 100%;
      width: 50%;
      background-color: white;
      display: flex;
      justify-content: center;

      .ass-left-in {
        background-color: #d4ddeb;
        height: 98%;
        width: 88%;
        border-radius: 15px;
        margin-left: 20px;

        .ass-left-text {
          height: 70%;
          background: transparent;

          .ass-input {
            text-align: top;
            flex: 0.4;
            border: none;
            outline: none;
            margin: 0 25px;
            font-size: 10px;
            background-color: #d4ddeb;
          }
        }

        .ass-left-icon {
          height: 30%;
          background-color: #d4ddeb;
          background: transparent;
          display: flex;
          flex-direction: row;

          .ass-left-icon1 {
            object-fit: contain;
            width: 15px;
            margin-left: 170px;
            background-color: #d4ddeb;
          }

          .ass-left-icon2 {
            object-fit: contain;
            width: 15px;
            margin-left: 10px;
            background-color: #d4ddeb;
          }

          .ass-left-icon3 {
            object-fit: contain;
            width: 15px;
            margin-left: 10px;
            background-color: #d4ddeb;
          }
        }
      }
    }

    .ass-right {
      height: 100%;
      width: 50%;
      background-color: white;
      display: flex;
      justify-content: center;

      .ass-right-in {
        background-color: #d4ddeb;
        height: 98%;
        width: 88%;
        border-radius: 15px;
        margin-right: 20px;

        .ass-right-head {
          width: 100%;
          height: 20%;
          background: transparent;

          .ass-right-head-text {
            background: transparent;
            font-family: 'Microsoft Yahei';
            font-size: 8px;
            font-weight: bold;
            letter-spacing: 1px;
            margin-left: 15px;
          }
        }

        .ass-right-main {
          width: 100%;
          height: 75%;
          background: transparent;

          .ass-right-bar {
            display: flex;
            flex-direction: row;
            background: transparent;

            .ass-right-bar-icon {
              object-fit: contain;
              width: 10px;
              margin-left: 18px;
              background: transparent;
            }

            .ass-right-bar-input {
              width: 190px;
              border-radius: 5px;
              margin-left: 10px;
              display: flex;
              align-items: center;

              .ass-right-bar-input-content {
                margin-left: 8px;
                outline: none;
                border: none;
              }

              .ass-right-bar-input-content::placeholder {
                font-size: 8px;
                letter-spacing: 1px;
              }
            }
          }
        }
      }
    }
  }
}

input::placeholder {
  color: b7bbc1;
}

.othpart {
  display: flex;
  flex-direction: row;
  align-items: center;

  .other-icon {
    height: 100px;
    border-radius: 15px;
    margin: 0 20px;
  }

  .other-text {
    display: flex;
    flex-direction: column;
    background-color: white;
    height: 70%;
    margin-right: 20px;

    .other-text-up {
      margin-top: 15px;
      background-color: white;
      font-family: 'Microsoft JhengHei';
      font-size: 15px;
      letter-spacing: 1px;
      font-weight: bold;
    }

    .other-text-down {
      margin-top: 15px;
      background-color: white;
      color: #b1b1b1;
      font-family: 'Microsoft JhengHei';
      font-size: 8px;
      letter-spacing: 1px;
    }

  }
}

.asspart-main {
  height: 70%;
  width: 85%;
  margin-bottom: 10px;
  border-radius: 15px;
  background-color: #e2ebf4;
  display: flex;
  align-items: center;

  .ass-icon {
    height: 100px;
    border-radius: 15px;
    margin: 0 20px;
  }

  .ass-text {
    display: flex;
    flex-direction: column;
    background-color: #e2ebf4;
    height: 70%;

    .ass-text-up {
      background-color: #e2ebf4;
      font-family: 'Microsoft Yahei';
      font-size: 8px;
      letter-spacing: 1px;
      font-weight: bolder;
    }

    .ass-text-down {
      margin-top: 30px;
      background-color: #e2ebf4;
      color: #777675;
      font-family: 'Microsoft Yahei';
      font-size: 8px;
      letter-spacing: 1px;
      line-height: 18px;
    }
  }
}

.asspart-head {
  margin-bottom: 10px;
  background-color: white;
  border-radius: 1000px;
  width: 100%;
}

.small-arrow {
  width: 8px;
  margin-left: 20px;
  background-color: white;
}

.small-arrow-text {
  font-family: 'Microsoft JhengHei';
  font-size: 13px;
  font-weight: 550;
  margin-left: 5px;
  background-color: white;
}

.ask-left {
  display: flex;
  justify-content: center;
  flex-direction: column;

  .ask-input {
    text-align: top;
    flex: 0.4;
    border: none;
    outline: none;
    margin: 0 25px;
    background-color: white;
  }

  .ask-info {
    flex: 0.4;
    background-color: #f0f4f9;
    border-radius: 20px;
    margin: 0 25px;
  }

  .ask-foot {
    flex: 0.2;
    background-color: white;
    border-radius: 30px;
    align-items: center;
    display: flex;

    .ask-icon1 {
      margin-left: 750px;
      width: 24px;
      background-color: white;
    }

    .ask-icon2 {
      margin-left: 15px;
      width: 24px;
      background-color: white;
    }
  }
}

.right-footer {
  display: flex;
  justify-content: center;

  .footer-text {
    font-family: 'Microsoft Yahei';
    font-size: 10px;
    padding: 0 20px;
    margin-top: 40px;
  }

  .footer-text:not(:last-child) {
    border-right: solid #d3d3d3 1px;
  }
}

.right-container {
  height: 100%;
  flex-direction: column;

  .right-footer {
    display: flex;
    flex: 1;
  }
}

.right-head {
  top: 20px;
  height: 30px;
  width: 100%;
  display: flex;
  align-items: center;
}

.big-arrow {
  width: 20px;
  margin-left: 40px;
}

.big-arrow-text {
  font-family: 'Microsoft Yahei';
  font-weight: 550;
  margin-left: 7px;
}

.right-main {
  width: 100%;
  display: flex;
  flex-direction: column;

  .ask {
    width: 100%;
    height: 340px;
    display: flex;
    flex-direction: column;
    align-items: center;

    .ask-main {
      background-color: #e7f1ff;
      margin-top: 20px;
      height: 90%;
      width: 95%;
      border-radius: 30px;
      display: flex;
      align-items: center;

      .ask-left {
        background-color: white;
        height: 82%;
        flex: 0.6;
        border-radius: 30px;
        margin: 0 28px;
      }
    }
  }

  .assistant {
    width: 100%;
    height: 220px;
    margin-top: 20px;
    flex-direction: column;
    display: flex;

    .assistant-main {
      display: flex;
      align-items: center;
      flex: 1;
      margin-top: 10px;

      .assistant-left {
        height: 100%;
        flex: 0.62;
        flex-direction: row;
        display: flex;
        align-items: center;
        margin: 0 30px;

        .asspart {
          height: 100%;
          background-color: white;
          border-radius: 15px;
          flex-shrink: 1;
          flex-basis: 500px;
          margin: 0 8px;
          flex-direction: column;
          display: flex;
          align-items: center;
          justify-content: center;
        }
      }

      .assistant-right {
        height: 100%;
        background-color: white;
        flex: 0.38;
        border-radius: 15px;
        margin-right: 40px;
      }
    }
  }

  .other {
    width: 100%;
    height: 190px;
    margin-top: 20px;
    flex-direction: column;
    display: flex;

    .other-main {
      flex: 1;
      display: flex;
      flex-direction: row;
      margin-left: 20px;

      .othpart {
        background-color: white;
        border-radius: 15px;
        flex-shrink: 1;
        flex-basis: 300px;
        margin: 10px 25px;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;

        .othpart-left {
          flex: 0.4;
          height: 100%;
          margin-left: 20px;
          display: flex;
          align-items: center;
          justify-content: center;
          background: transparent;

          .othpart-left-icon {
            background: transparent;
          }
        }

        .othpart-right {
          flex: 0.6;
          height: 100%;
          background: transparent;
          display: flex;
          align-items: center;

          .othpart-right-text {
            font-family: 'Microsoft JhengHei';
            font-size: 15px;
            font-weight: bold;
            background: transparent;
          }
        }
      }
    }
  }
}

.right-log-in {
  width: 100px;
  position: absolute;
  top: 0;
  right: 0;
  margin: 20px;
}

.head-area {
  display: flex;
  flex-direction: row;
  margin-top: 30px;

  .head-icon {
    height: 50px;
    margin: 0 10px;
    background: transparent;
  }

  .head-text {
    justify-content: center;
    align-items: center;
    display: flex;
    flex-direction: column;

    .uptext {
      font-family: 'STCaiyun';
      font-size: 20px;
      margin-bottom: 5px;
    }

    .downtext {
      font-family: 'Microsoft Yahei';
      font-size: 10px;
      font-weight: bold;
    }
  }
}

.right-container {
  display: flex;
  flex-direction: column;
  width: 100%;

  .header {
    width: 100%;
    height: 80px;
    justify-content: center;
    align-items: center;
    display: flex;
  }
}

.log-in {
  width: 60px;
  position: fixed;
  bottom: 40px;
}

.left-btn {
  background-color: #eaf1f9;
  width: 80px;
  height: 60px;
  margin: 5px;
  border-radius: 15px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #0f67fe;
  flex-direction: column;

  .left-icon {
    display: flex;
    width: 20px;
    margin-bottom: 5px;
  }

  .left-text {
    font-size: small;
    margin: 0px;
    color: #000;
    font-family: 'Microsoft Yahei';
    font-weight: bold;
  }
}

.left-btn:hover {
  color: #dae4f2;
}

.top-btn {
  margin-top: 50px;
}

.logo-white {
  width: 70px;
  margin-top: 10px;
  background: transparent;
}

.container {
  display: flex;
  min-height: 100vh;
}

.left-aside {
  width: 80px;
  background-color: #edf8fc;
  padding: 20px;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  border-right: solid #eaf1f9 1px;
}
</style>
