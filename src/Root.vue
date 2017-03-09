<template>
    <div class='container'>
      <div class="row">
        <div class="col-xs-10 col-xs-offset-1 col-sm-6 col-sm-offset-3">
          <br>
            <div class='head'>
              <img class='jet' height='40' width='40' src='./assets/jet.png'>
            </div>
            <br>
            <div class='filter'>
              <input type='text' v-on:keyup.enter='searchAlbums()' class='form-control fontAwesome' id="query" placeholder="&#xf002; Search for products"></input>
            </div>
            <!-- People -->
            <div class="row">
              <div class="col-sm-4 col-md-4 thumb">
                <div class="thumbnail">
                  <img src="./assets/money1.png" alt="...">
                  <div class="caption">
                    <h3>Thumbnail</h3>
                    <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                  </div>
                </div>
              </div>
              <div class="col-sm-4 col-md-4 thumb">
                <div class="thumbnail">
                  <img src="./assets/money1.png" alt="...">
                  <div class="caption">
                    <h3>Thumbnail</h3>
                    <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                  </div>
                </div>
              </div>
              <div class="col-sm-4 col-md-4 thumb">
                <div class="thumbnail">
                  <img src="./assets/money1.png" alt="...">
                  <div class="caption">
                    <h3>Thumbnail</h3>
                    <p>Cras justo odio, dapibus ac facilisis in, egestas eget quam. Donec id elit non mi porta gravida at eget metus. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                  </div>
                </div>
              </div>
            </div>

            <!-- Modal -->
            <div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe src="https://player.vimeo.com/video/134241981?color=ffffff&title=0&byline=0&portrait=0" width="500" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal2" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/DQpz22UgKEs" frameborder="0" allowfullscreen></iframe>                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal3" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/EP_z5GjBajc" frameborder="0" allowfullscreen></iframe>                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal4" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/8eFBjk_ugjo" frameborder="0" allowfullscreen></iframe>                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal5" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/hBUZbdPvtto" frameborder="0" allowfullscreen></iframe>                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal6" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/12jJBlVGjOk" frameborder="0" allowfullscreen></iframe>                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal7" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/DdKQtSp__sw" frameborder="0" allowfullscreen></iframe>                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal8" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/c370voFGAts" frameborder="0" allowfullscreen></iframe>                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal9" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/nHmNqgd3SuQ" frameborder="0" allowfullscreen></iframe>                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal10" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/679lZ2Cd2Uw" frameborder="0" allowfullscreen></iframe>
                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal11" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/pe-25rv-jLY?list=PLBYb7zrLyJBWjvQsjmbz_Nsk39sFCwKRB" frameborder="0" allowfullscreen></iframe>                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal12" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/Wmw6BJUKtc0?list=PLBYb7zrLyJBWjvQsjmbz_Nsk39sFCwKRB" frameborder="0" allowfullscreen></iframe>
                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal13" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/TsACmfjbPao?list=PLBYb7zrLyJBWjvQsjmbz_Nsk39sFCwKRB" frameborder="0" allowfullscreen></iframe>                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal14" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/5E08uTp9IVU?list=PLBYb7zrLyJBWjvQsjmbz_Nsk39sFCwKRB" frameborder="0" allowfullscreen></iframe>
                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal15" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/592aQgFsFoY" frameborder="0" allowfullscreen></iframe>
                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
            <!-- Modal -->
            <div class="modal fade" id="myModal16" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <img class='' height='40' width='40' src='./assets/jet.png'>
                  </div>
                  <div class="modal-body">
                    <iframe width="500" height="315" src="https://www.youtube.com/embed/dX9a2XrMKJg" frameborder="0" allowfullscreen></iframe>
                  </div>
                </div>
              </div>
            </div>
            <!-- Modal -->
        </div>
      </div>

      <div class="row">
        <div class="col-xs-11 col-xs-offset-1 col-sm-6 col-sm-offset-3">

          <div class="blocs" v-for='image in images'>
              <img class='rounded' src='./assets/money1.png' height='127' width='127' data-toggle="modal" data-target="#myModal">
              <img class='rounded' src='./assets/green.png' height='127' width='127' data-toggle="modal" data-target="#myModal2">
              <img class='rounded' src='./assets/money2.png' height='127' width='127' data-toggle="modal" data-target="#myModal3">
              <img class='rounded' src='./assets/money1.png' height='127' width='127' data-toggle="modal" data-target="#myModal4">
          </div>
          <div class="blocs" v-for='image in images'>
            <img class='rounded' src='./assets/green.png' height='127' width='127' data-toggle="modal" data-target="#myModal5">
            <img class='rounded' src='./assets/money2.png' height='127' width='127' data-toggle="modal" data-target="#myModal6">
            <img class='rounded' src='./assets/green.png' height='127' width='127' data-toggle="modal" data-target="#myModal7">
            <img class='rounded' src='./assets/money1.png' height='127' width='127' data-toggle="modal" data-target="#myModal8">
          </div>
          <div class="blocs" v-for='image in images'>
            <img class='rounded' src='./assets/money1.png' height='127' width='127' data-toggle="modal" data-target="#myModal9">
            <img class='rounded' src='./assets/green.png' height='127' width='127' data-toggle="modal" data-target="#myModal10">
            <img class='rounded' src='./assets/money2.png' height='127' width='127' data-toggle="modal" data-target="#myModal11">
            <img class='rounded' src='./assets/green.png' height='127' width='127' data-toggle="modal" data-target="#myModal12">
          </div>
          <div class="blocs blocs-last" v-for='image in images'>
            <img class='rounded' src='./assets/money2.png' height='127' width='127' data-toggle="modal" data-target="#myModal13">
            <img class='rounded' src='./assets/money1.png' height='127' width='127' data-toggle="modal" data-target="#myModal14">
            <img class='rounded' src='./assets/green.png' height='127' width='127' data-toggle="modal" data-target="#myModal15">
            <img class='rounded' src='./assets/money2.png' height='127' width='127' data-toggle="modal" data-target="#myModal16">
          </div>

            <div class='footer'>
              <img class='jet' height='40' width='40' src='./assets/jet.png'>
            </div>
            <div class='footer2'>
              <div class='row'>
                <div class='col-sm-12'>
                  <div class='col-sm-3 col-sm-offset-3'>
                    <h6><a href='mailto:diogenis.panagiotis@gmail.com'>Email</a><h6>
                    <h6><a href='linkedin.com/in/DiogenisPanagiotis'>LinkedIn</a><h6>
                  </div>
                  <div class='col-sm-3 col-sm-offset-1'>
                    <h6><a href='github.com/DiogenisPanagiotis'>Github</a><h6>
                    <h6><a href='angel.co/diogenispanagiotis'>Angel</a><h6>
                  </div>
                </div>
              </div>
            </div>
        </div>
      </div>
    </div>
</template>

<script>
  import $ from 'jquery';
  import pic from './assets/green.png';
  let audioObject = null;
  let API_URL = 'https://api.shutterstock.com/v2';

  export default {
    data(){
      return {
        startPage: true,
        products: [],
        blocs: ['#8200ff', '#0c9', '#6800cc', '#CC64FF', '#22C3FD'],
        images: [
          '/assets/green.png'
        ],
        keywords: []
      }
    },
    mounted(){
      this.getProducts();
    },
    methods: {
      getProducts: function(){
        let that = this;
        let query = 'supplies';
        this.$http.get('https://pixabay.com/api?key=4756359-f31934d2a8bbd8b2f7b572ac8', {params: {q: query}})
          .then(res => {
            console.log(res.body);
            for (var i = 0; i < res.body.hits.length; i++) {
              let image = res.body.hits[i].previewURL;
              that.products.push(image);
            }
          });
      },
      searchAlbums: function(query){
        this.products = [];
        query = document.getElementById('query').value;
        let that = this;
        // this.startPage = false;

        this.$http.get('https://pixabay.com/api?key=4756359-f31934d2a8bbd8b2f7b572ac8', {params: {q: query}})
        .then(res => {
          for (var i = 0; i < res.body.hits.length; i++){
            let image = res.body.hits[i].previewURL;
            that.products.push(image);
          }
        });
      }
    }
  }
</script>

<style scoped>
  .head {
    height: 100px;
    width: 555px;
    border-radius: 3px;
    background-color: #8225FA;
    /*background-color: #3897f0;*/
  }
  .thumb {
    padding-left: 12px;
  }
  span {
    color: #fff;
    text-shadow: none;
    font-size: 30px;
    margin-right: 5px;
  }
  .glostick {
    background: linear-gradient(to right, #8D728A, #F17A87);
    border-radius: 3px;
    width: 555px;
    height: 100px;
  }
  .thing {
    display: inline-block;
  }
  .text {
    margin-left: 35%;
    margin-top: 40%;
    text-transform: uppercase;
    color: #fff;
  }
  .jet {
    margin-top: 32px;
    margin-left: 262px;
    transition: 1s ease-out;
    opacity: 10%;
    border-radius: 25px;
  }
  .jet:hover {
    transform: rotate(360deg);
  }
  .modal-header {
    background-color: #8225FA;
  }
  .modal-body {
    padding: 50px;
  }
  .filter {
    padding: 40px;
    background: #efefef;
    background: #0c9;
    border-radius: 3px;
    margin-bottom: 10px;
  }
  h5 {
    font-family: 'Roboto';
    color: #fff;
    text-align: center;
    padding-top: 40px;
  }
  .albums {
    padding-left: 10px;
    display: inline;
  }
  .blocs {
    padding-left: 10px;
    display: inline;
  }
  .blocs-last {
    margin-bottom: 10px;
  }
  .rounded {
    border-radius: 3px;
    margin-bottom: 7px;
    margin-left: 4px;
    /*border-style: solid;
    border-width: 25px;
    border-color: #8200ff;*/
  }
  .rounded:hover {
    cursor: pointer;
    border: 5px solid #fff;
    border-radius: 8px;
    opacity: 0.5;
  }
  .playing {
    border: 5px solid #fff;
    border-radius: 8px;
    opacity: 0.9;
  }
  input {
    border-radius: 1px;
  }
  input:focus {
    border: 1px solid #ccc;
    box-shadow: none;
  }
  .fontAwesome {
    font-family: 'Helvetica', FontAwesome, sans-serif;
  }
  .footer {
    height: 100px;
    width: 555px;
    border-radius: 3px;
    background-color: #8225FA;
    margin-top: 2px;
  }
  .footer2 {
    height: 100px;
    width: 555px;
    border-radius: 3px;
    background-color: #3A3F44;
    margin-top: 15px;
    margin-bottom: 20px;
  }
  .madeWith {
    /*color: #4D3982;    */
    font-size: 14px;
    color: #fff;
  }
  a {
    color: #fff;
  }
  h6 {
    font-size: 11px;
  }
  .col-sm-3 {
    padding-top: 25px;
  }
  .fa-cloud {
    font-size: 1.7em;
    color: #fff;
  }
  .fa-cloud:hover {
    color: #4D3982;
  }
</style>
