# GeometryCalc
JS in HTML 
in the js add an event listener 
document.getElementById( -id to use in the UI- ).addEventListener('click', nameofJSfunction);

HTML TEMPLATE FOR UI Calc Area 

<div class="container">
       <div class="New_Area">
          <h3>Area of a Triangle </h3>      
            <div id=-"NAME OF ID FROM ABOVE" ->
                <div class="row justify-content-md-center">
                    <div class="formula">
                    <p class="text-center">A=1/2(B*H)</p>
                   </div>
                 </div>
            <div class="row">  
                <div class="col-sm" >
                    <h6 class="text-center">Base </h6>
                    <input type="number" id='base-tri NEEDS TO BE UNIQUE' class="form-control shadow-lg" placholder="base" >
                 </div>
                 <div class="col-sm">
                   <h6 class="text-center">Height </h6>
                   <input type="number" id='height-tri NEEDS TO BE UNIQUE' class="form-control shadow-lg" placholder="height">
                  </div>
                <div class="col-sm">
                  <div class ="AnswerSection">
                   <p class="text-center"> <span id='answer'></span> </p>
                  </div>
                  </div>
              </div>
              <div class="row">
               <div class="col text-center">
                <button type="submit" value='submit' id='submit' class="btn btn-primary justify-center">Submit</button>
               </div>
              </div>
            </div>
          </div>
      </div>
