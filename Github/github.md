- clearfix
  
  ```
  .clearfix::after {
      content: "";
      clear: both;
      display: block;
  }
  .float-left {
      float: left;   
  }
  .float-right {
      float: right;
  }
  ```

- form 
  
  ```
  <form method="POST" action="">
      <button type="submit">으
  </form>
  ```
  
  form 태그 하위요소로 버튼을 만들고 type을 submit으로 지정해주면 action이 작동된다.
  
  
  
  
  

- flex
  
  flex-grow, flex-shirink, flex-basis 플렉스 컨테이너의 속해있는 아이템의 속성을 정의
  
  flex-basis: auto;(default) 이지만 flex 단축속성으로 사용시 0이 default가 된다.
  
  flex: flex-grow shirink basis



- video
  
  ```
  video {
      max-width: 500px;
  }
  .video-ratio {
      height:0;
      padding-top: 56.25%
      position: relative;
  }
  .iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
  }
  ```
  
  height값을 정해주면 픽스가 되니 padding-top을 이용 
  
  부모의 width값에 영향을 받는다.  500 : x = 16 : 9 ==> 56.25%


