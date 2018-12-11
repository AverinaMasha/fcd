  <template> 
    <div class="counter">
      <button class="counter_minus">-</button>
      <input  value="1" min="1" type="number" disabled/>
      <button class="counter_plus">+</button>
    </div>
  </template>

  <script>
  export default {};
  </script>

  <style>
  body {
    font-size: 52px;
    font-family: "Monaco", "Courier", monospace;
  }

  .counter input { 
   border: none;
   width: 150px;
   text-align: center;
   color: #1FA19C; 
   background-color: white; 
  }

  .counter button{
   background-color: #1FA19C; 
   color: white; 
   border-radius: 4px;
   width: 25px;
   height: 22px;
  }
  </style>
