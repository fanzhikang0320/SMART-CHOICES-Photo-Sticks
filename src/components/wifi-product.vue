<template>
  <div class="product-wrapper">
      <div :class="{'product-item': true, 'first-item': index == 0, 'last-item': index == productList.length - 1}" v-for="(product,index) in productList" :key="index">
          <div class="circle" v-if="index != productList.length- 1">
              <span class="num">{{index + 1}}</span>
          </div>
          <div class="corner-box" v-if="index == 0">
              <span class="text">50% Discount Today!</span>
          </div>
          <div class="big-title" v-if="index == productList.length - 1">The Most Popular Photo Stick Devices In 2020</div>
          <a :href="product.link" @click.stop="handleExecute" target="_blank" class="product-link-box">
            <div class="product-container">
                <div class="product-container-left">
                    <div class="picture-box">
                        <img :src="product.picture" :alt="product.name" class="picture">
                    </div>
                    <div class="desc-list-box">
                        <h2 class="product-name">{{product.name}}</h2>
                        <ul class="list-box">
                            <li v-for="(item,id) in product.list" :key="id">
                                <span class="icon"></span>
                                <p class="text">{{item.text}}</p>
                            </li>
                        </ul>
                        <p class="buys" v-if="index == 0 || index == productList.length - 1">More than {{product.buys}} people choose InfinitiKloud Today!</p>
                    </div>
                </div>
                <div class="product-container-right">
                    <p class="good">
                        <span class="text">{{index == 0 || index == productList.length - 1 ? 'Excellent': index == 1 ? 'Very Good': 'Good'}}</span>
                        <span class="king-icon" v-if="index == 0 || index == productList.length - 1"></span>
                        <span class="good-icon" v-if="index == 1"></span>
                    </p>
                    <p class="rate-box"><span class="score">{{product.score}}</span><span>/10</span></p>
                    <a :href="product.link" target="_blank" @click.stop="handleExecute" class="btn">
                        <span class="text">Visit Site</span>
                        <span class="icon"></span>
                    </a>
                    <!-- <a :href="product.reviewLink" class="review">Read Our Review</a> -->
                </div>
            </div>
          </a>
      </div>
      
  </div>
</template>

<script>
export default {
    data() {
        return {
            productList: [
                {
                    id: 1,
                    name: 'InfinitiKloud',
                    picture: require('@/assets/image/photoStick/IK.png'),
                    link: 'https://www.flrdra.com/7QLQCMW/4R4RHZ9/?uid=5005',
                    reviewLink: '',
                    buys: 586,
                    list: [
                        {
                            text: 'One-click easy backup'
                        },
                        {
                            text: 'Easily add more memory'
                        },
                        {
                            text: 'FREE USB C and micro USB adapter'
                        },
                        
                        {
                            text: 'Great price ($34.99 for 32GB)'
                        },
                        {
                            text: 'Build-in MicroSD card slot'
                        },
                        {
                            text: 'Compatible with: PC, Windows, Android and Mac '
                        },
                        {
                            text: '30-day money back guarantee'
                        }
                    ],
                    score: '9.8'

                },
                {
                    id: 2,
                    name: 'MemorySafeX',
                    picture: require('@/assets/image/photoStick/MS.png'),
                    link: 'https://hypertechx.com/ps/memorysafex/index.php?net=9785&amp;aff={AFFID}&amp;sid={SUBID}&amp;cid={CLICKID}',
                    reviewLink: '',
                    buys: 788,
                    list: [
                        {
                            text: 'Easy to use'
                        },
                        {
                            text: 'Compatible with all media formats '
                        },
                        {
                            text: 'Light and compact for storage and travel'
                        },
                        {
                            text: 'Large capacity'
                        },
                        {
                            text: 'Transfer your media safely'
                        },
                        {
                            text: 'Works without Internet'
                        }
                    ],
                    score: '9.6'

                },
                {
                    id: 3,
                    name: 'The Photo Stick',
                    picture: require('@/assets/image/photoStick/TPS.png'),
                    link: 'https://deals.getphotostick.io/LC7FMRH/SMDD2L/?uid=264',
                    reviewLink: '',
                    buys: 788,
                    list: [
                        {
                            text: 'Increases your Wi-Fi coverage'
                        },
                        {
                            text: 'Has 3 Antennas'
                        },
                        {
                            text: 'Blasting a strong, steady signal'
                        },
                        {
                            text: 'Faster 5GHz protocol'
                        },
                        {
                            text: '30-day money back guarantee'
                        }
                    ],
                    score: '9.3'

                },
                {
                    id: 4,
                    name: 'FlashDrive',
                    picture: require('@/assets/image/photoStick/FD.png'),
                    link: 'https://photostick.elitegadgetreviews.com/photostick/en/g/indexen.html',
                    reviewLink: '',
                    buys: 788,
                    list: [
                        {
                            text: 'Huge 64GB storage capacity'
                        },
                        {
                            text: 'Compatible with numerous devices'
                        },
                        {
                            text: 'Connects directly to your device'
                        },
                        {
                            text: 'Takes care of you and your family’smemories'
                        }
                    ],
                    score: '9.0'

                },
                
                {
                    id: 1,
                    name: 'InfinitiKloud',
                    picture: require('@/assets/image/photoStick/IK.png'),
                    link: 'https://www.flrdra.com/7QLQCMW/4R4RHZ9/?uid=5005',
                    reviewLink: '',
                    buys: 586,
                    list: [
                        {
                            text: 'One-click easy backup'
                        },
                        {
                            text: 'Easily add more memory'
                        },
                        {
                            text: 'FREE USB C and micro USB adapter'
                        },
                        
                        {
                            text: 'Great price ($34.99 for 32GB)'
                        },
                        {
                            text: 'Build-in MicroSD card slot'
                        },
                        {
                            text: 'Compatible with: PC, Windows, Android and Mac '
                        },
                        {
                            text: '30-day money back guarantee'
                        }
                    ],
                    score: '9.8'

                }
            ]
        }
    },
    methods: {
        handleExecute() {
            window.execute();
        }
    }

}
</script>

<style lang="less" scoped>
@import url('../assets/css/wifi-product.less');
</style>