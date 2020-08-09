<template>
  <div class="mosquito-wrapper">
        <div class="maskLayer">
                <div class="mask-content ">
                    <span class="close"></span>
                    <a :href="mainLink" @click.stop="handleExecute" target="_blank" class="mask-box clearfix">
                        <div class="mask-left">
                            <img src="@/assets/image/photoStick/alert-ad.jpg" alt="" class="ad">
                        </div>
                        <div class="mask-right">
                            <p class="offer">Limited Time Offer</p>
                            <p class="save"><span>SAVE</span><strong>50% MONEY</strong></p>
                            <p class="OEI">Offer Expires In</p>
                            
                            <div class="date-area">
                                <div class="time-box colon">
                                    <span class="text">Hours</span>
                                    <div class="time">
                                        <span class="hours-decade">0</span>
                                        <span class="hours-unit">0</span>
                                    </div>
                                </div>
                                <div class="time-box colon">
                                    <span class="text">Minutes</span>
                                    <div class="time">
                                        <span class="minutes-decade">0</span>
                                        <span class="minutes-unit">0</span>
                                    </div>
                                </div>
                                <div class="time-box">
                                    <span class="text">Seconds</span>
                                    <div class="time">
                                        <span class="seconds-decade">0</span>
                                        <span class="seconds-unit">0</span>
                                    </div>
                                </div>
                            </div>
                            <p class="desc">30 Days Money Back Guarantee</p>
                            <a :href="mainLink" @click.stop="handleExecute" target="_blank" rel="noopener noreferrer" class="btn">Get the discount today!</a>
                        </div>
                    </a>
                </div>
        </div>
      <header class="mosquito-header">
          <div class="header-left">
                <img src="@/assets/image/logo.png" alt="SMART CHOICES" class="logo">
                <p class="text">Best soluion to backup your files</p>
          </div>
          <a href="/" class="btn">Top4 Photo Stick Devices</a>

      </header>
      <section class="banner">
          <div class="banner-container">
               <div class="banner-content">
                    <h1 class="g">2020’s TOP 4</h1>
                    <h1 class="a">Photo Stick Devices</h1>
                </div>
          </div>
          
      </section>
      <main class="container">
          <div class="desc-area">
              <h2 class="area-title">The Best Photo Stick Devices In 2020</h2>
              <div class="desc-content">
                  <p>Do you need a solution to safeguard the photos, videos, and important documents you stored on your device?  Our researchers have bought & tested some of 2020's most popular photo backup devices. We looked at price, product quality, ease of use, range, effectiveness and discounts, and compiled the 4 choices below:</p>
              </div>
          </div>
          <div class="product-area">
              <p class="product-area-title">Here is our Top 4 List for Best Photo Stick Devices 2020:</p>
              <WifiProduct/>
          </div>
          <div class="why-area">
              <h2 class="area-title">Why infinitiKloud is our top choice?</h2>
              <div class="why-container">
                  <div class="img-box">
                      <div class="img-item">
                          <img src="@/assets/image/photoStick/sudu.svg" alt="" class="svg">
                          <span class="text">Fast Speed</span>
                      </div>
                      <div class="img-item">
                          <img src="@/assets/image/photoStick/lianjie.svg" alt="" class="svg">
                          <span class="text">Easy Connection</span>
                      </div>
                      <div class="img-item">
                          <img src="@/assets/image/photoStick/zhiliang.svg" alt="" class="svg">
                          <span class="text">High Quality</span>
                      </div>
                      <div class="img-item">
                          <img src="@/assets/image/photoStick/storage.svg" alt="" class="svg">
                          <span class="text">Large Storage</span>
                      </div>
                  </div>
                  <div class="content">
                    <p>InfintiKloud™ is ultra portable, handheld, and can store all your important and private files and photos so that you are 100% backed up. No large cloud provider, like Facebook or Amazon, is holding onto (and snooping through) your files and folder. This means you are secure, private, and can have the confidence that if your computer, tablet, or phone fails/is stolen, you are <strong>100% protected</strong> and backed up.</p>
                    <p>If you’re in the United States, you’ll be able to receive <strong>free shipping</strong>. That’s right. You won’t pay a dime to ship your product. The company also accepts a variety of different payment methods, including all major credit cards and PayPal. The site is Shopify secure, so you don’t have to worry about your personal information at any time during the transaction.</p>
                    <p>The InfinitiKloud gets our seal of approval with a 96% rating. It’s a superb product with a lot of promise, and it can help save anyone’s digital memories. The manufacturer is so confident in their product that they even offer a <strong>30-day money back guarantee</strong>. Built-in search functionality allows you to search every file and folder in just seconds to ensure that all of your memories are found and backed up. </p>
                    <p>Thousands of files are backed up in minutes – videos take longer – but you’ll be able to back up files in minutes versus hours. Storage capacity up to <strong>64 GB</strong>, or enough to back up <strong>45,000 pictures and videos</strong>. On-going backups are offered, providing instant weekly backups of files so that you never have to worry about losing your memories again. All you have to do is plug-in The InfinitiKloud into a USB port and hit the “Go” button. That’s all.</p>
                    <p>The InfinitiKloud will do the rest for you. Let’s say that you need to set this up for a family member. You can leave the unit in the USB drive so that memories are backed up every week. This is a great option for anyone who is setting the unit up for their very non-tech savvy parent.</p>
                  </div>
              </div>
          </div>
          <div class="how-area">
              <h2 class="area-title">How to back up your files？</h2>
              <div class="how-container">
                  <div class="step-item">
                      <p class="step">Step 1.</p>
                      <img src="@/assets/image/photoStick/step1.png" alt="" class="picture">
                      <p class="text">Plug InfinitiKloud into your computer or Android device's <strong>USB port</strong>.</p>
                  </div>
                  <div class="step-item">
                      <p class="step">Step 2.</p>
                      <img src="@/assets/image/photoStick/step2.png" alt="" class="picture">
                      <p class="text">Find and open InfinitiKloud in your File Explorer or install the InfinitiKloud app.</p>
                  </div>
                  <div class="step-item">
                      <p class="step">Step 3.</p>
                      <img src="@/assets/image/photoStick/step3.png" alt="" class="picture">
                      <p class="text">Click <strong>START</strong> to automatically locate and back up selected file types.</p>
                  </div>

              </div>
          </div>
          <div class="special-area">
              <div class="special-container">
                    <h3 class="offer">Special Offer on Now!</h3>
                    <p class="sub">Now there is a special offer, but such a low price, there may not be much left! </p>
                    <p class="sub">So do it now!</p>
                    <p class="get-up">Get Up To <span class="big-red">50% OFF</span> Your <strong>InfinitiKloud</strong> Today!</p>
                    <img src="@/assets/image/photoStick/special-ad.jpg" alt="" class="picture">
                    <a :href="mainLink" target="_blank" @click="handleExecute" rel="noopener noreferrer" class="btn">Get Your InfinitiKloud Now!</a>
                </div>
          </div>
          <div class="faq-area">
              <h2 class="area-title">FAQ</h2>
              <div class="question-box">
                  <div class="question-item" v-for="(item,index) in questionData" :key="index">
                      <h3 class="question-title">{{item.title}}</h3>
                      <div class="question-content" v-html="item.content"></div>
                  </div>
              </div>
          </div>
      </main>
  </div>
</template>

<script>
import WifiProduct from '@/components/wifi-product.vue'
import $ from 'jquery'
export default {
    components: {
        WifiProduct
    },
    data() {
        return {
            mainLink: 'https://www.flrdra.com/7QLQCMW/4R4RHZ9/?uid=5005',
            questionData: [
                {
                    title: 'Why do I need this USB Gagdet for backups?',
                    content: `<p>In principle, the product is aimed at every user of a computer and who would like to store their memories and important files separately so that they can continue to use them. Both young and old benefit from its use, because both generations have data that they would hate to lose in a data crash. Gender is irrelevant, because the Private Cloud is easy for everyone to use. It is also the ideal product for those who don’t want to go through a costly backup process and are looking for an easier way.</p>`
                },
                {
                    title: 'What is the transfer speed of backup stick?',
                    content: `<p>The most of products' transfer speed is over 60MB/s.</p>`
                },
                {
                    title: 'What is the amount of storage space?',
                    content: `<p>It depends on the type of product you choose, most of them available in 3 different storage options which include 32gb, 64gb, and 128gb.</p>`
                },
                {
                    title: 'Can I transfer from photos from my iPhone?',
                    content: `<p>If the backup stick you choose is compatible with IOS. You will be able to transfer your photos from your iPhone in it.</p>`
                }
            ],
            timer: null,
            count: 0
        }
    },
    methods: {
        /**
         * 倒计时
         */
        countDown() {
            //结束时间
            let finishTime = new Date('2020/7/31').getTime();
            let startTime = new Date(new Date().toLocaleDateString()).getTime();
            let intervalTime = 0,
                day = 0,
                hours = 0,
                minutes = 0,
                seconds = 0;
            let that = this;
            this.timer = setInterval(function () {
                if (finishTime - new Date().getTime() <= 0) {
                     finishTime = new Date(new Date().toLocaleDateString()).getTime() + 1 * 24 * 60 * 60 * 1000;
                }
                intervalTime = finishTime - new Date().getTime();

                day =  Math.floor(intervalTime/(1000*60*60*24));
                hours = Math.floor(intervalTime / (60 * 60 * 1000) % 24) + day * 24;
                minutes = Math.floor(intervalTime / (60 * 1000) % 60);
                seconds = Math.floor(intervalTime / 1000 % 60); 
                that.renderTime(hours,minutes,seconds);
                
            },1000)
            
        },
        renderTime(hours,minutes,seconds) {
            let hoursObj = this.splitCell(hours);
            let minutesObj = this.splitCell(minutes);
            let secondsObj = this.splitCell(seconds);
            $('.hours-decade').text(hoursObj.decade);
            $('.hours-unit').text(hoursObj.unit);
            $('.minutes-decade').text(minutesObj.decade);
            $('.minutes-unit').text(minutesObj.unit);
            $('.seconds-decade').text(secondsObj.decade);
            $('.seconds-unit').text(secondsObj.unit);

        },
        splitCell(num) {
            let unit = Math.floor(num % 10);
            let decade = Math.floor(num / 10);
            return {
                unit: unit,
                decade: decade
            }
        },
        alert() {
            $('.maskLayer').css({
                display: 'block'
            })
            $('.mask-content').animate({opacity: 1,top: '50%'},500)
        },
        handleExecute() {
            window.execute();
        }
    },
    mounted() {
        this.countDown();
        let that = this;
        $('body').on('mouseenter',function () {
            $('body').one('mouseleave',function () {
                if (that.count == 0) {

                    that.alert();
                }
                that.count ++;
            })
        })
        $('.close').on('click',function (event) {
            event.stopPropagation();
            $('.maskLayer').css({
                display: 'none'
            })
            clearInterval(that.timer);
        })
        $('.maskLayer').on('click',function (e) {
            e.stopPropagation();
            $('.maskLayer').css({
                display: 'none'
            })
            clearInterval(that.timer);
        })
    },
    beforeDestroy() {
        $('body').off('mouseenter');
        clearInterval(this.timer);
        this.timer = null;
    }
}
</script>

<style lang="less" scoped>
@import url('../assets/css/Photo.less');
</style>