# CSS GRID

The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

## A grid layout consists of a parent element, with one or more child elements.

    <div class="grid-container">
      <div class="grid-item">1</div>
      <div class="grid-item">2</div>
      <div class="grid-item">3</div>
      <div class="grid-item">4</div>
      <div class="grid-item">5</div>
      <div class="grid-item">6</div>
      <div class="grid-item">7</div>
      <div class="grid-item">8</div>
      <div class="grid-item">9</div>
    </div>

## Example Code used in the repository

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 300px));
      justify-content: center;
      gap: 10px;
    }
    
    .grid-item {
      border: 2px solid black;
    }
    
    .grid-item img {
      width: 100%;
    }

### Learn more about css grid in: https://www.w3schools.com/css/css_grid.asp
