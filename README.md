# boxes-with-distinct-hover-effect
When utilizing cards or boxes, it’s helpful to create a hover effects that creates the allusion of depth so as to better indicate to the user that they are on a clickable item.

## Tutorial
For detailed instruction's, view Solodev's [How to Create Boxes with a Distinct Hover Effect](https://www.solodev.com/blog/web-design/how-to-create-boxes-with-a-distinct-hover-effect.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/g5dvr2f1/).

## HTML
The tutorial contains the following basic HTML markup.

```
<div class="container">
  <div class="row">
    <div class="col-md-4 col-sm-6 col-xl-4 my-3">
      <div class="card d-block h-100 box-shadow-hover pointer">
        <div class="pt-3 h-75p align-items-center d-flex justify-content-center">
          <img class="img-fluid w-xs-120p" src="https://raw.githubusercontent.com/solodev/boxes-with-distinct-hover-effect/master/images/valkyrie.png" alt="valkyrie ship image">
        </div>
        <div class="card-body p-4">
          <h3 class="h4"><strong>Valkyrie-1</strong></h3>
          <p>As the lean, mean “muscle” of the LunarXP fleet, the Valkyrie-1 series makes safe transportation from surface to orbit a reality.</p>
        </div>
      </div>
    </div>

    <div class="col-md-4 col-sm-6 col-xl-4 my-3">
      <div class="card d-block h-100 box-shadow-hover pointer">
        <div class="pt-3 h-75p align-items-center d-flex justify-content-center">
          <img class="img-fluid w-xs-120p" src="https://raw.githubusercontent.com/solodev/boxes-with-distinct-hover-effect/master/images/talon.png" alt="talon ship image">
        </div>

        <div class="card-body p-4">
          <h3 class="h4"><strong>Talon-2</strong></h3>
          <p>The Talon-2 series is the primary vehicle for crossing the colony and delivering both personnel and goods to habitats – from agriculture to engineering equipment.</p>
        </div>
      </div>
    </div>

    <div class="col-md-4 col-sm-6 col-xl-4 my-3">
      <div class="card d-block h-100 box-shadow-hover pointer">
        <div class="pt-3 h-75p align-items-center d-flex justify-content-center">
          <img class="img-fluid w-xs-120p" src="https://raw.githubusercontent.com/solodev/boxes-with-distinct-hover-effect/master/images/lunar-xplorer.png" alt="ship image">
        </div>
        <div class="card-body p-4">
          <h3 class="h4"><strong>Lunar XPlorer</strong></h3>
          <p>Often referred to as a “container ship in space,” the Lunar XPlorer is the flagship of the LunarXP fleet and the primary mode of transportation for people, equipment, and supplies to the moon.</p>
        </div>
      </div>
    </div>

  </div>
</div>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```