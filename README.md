# Simple SCSS

Simple SCSS is a short layouting SCSS file that you can use to create a template-looking simple styled layout for showcasing projects where the focus is not on the design but you still want your page to look nice.

It normalizes HTML tags and applies basic styling and responsive to a few tags. It also contains basic responsive classes such as rows and columns, and a basic menu.

Simple form:
```
  <form class="simple-form">
      ...
  </form>
```

Simple rows:
```--single``` - a width of 100%, 
```--half``` - a width of 50%, and 
```--third``` - a width of 33.3%

```xs``` - applied under 575px, 
```s``` - applied under 768px, 
```md``` - applied under 1024px, and 
```l``` - applied over 1024px

Example:
```
  <div class="simple-row simple-row--single-l"> ... </div>
  
  <div class="simple-row simple-row--half-l"> ... </div>
  <div class="simple-row simple-row--half-l"> ... </div>
  
  <div class="simple-row simple-row--third-l simple-row--half-s"> ... </div>
  <div class="simple-row simple-row--third-l simple-row--half-s"> ... </div>
  
  <div class="simple-row simple-row--third-l simple-row--single-s"> ... </div>
```

Simple buttons:
```
<button class="simple-button simple-button--secondary" type="submit">Cancel</button>

<button class="simple-button simple-button--primary" type="submit">Submit</button>
```

Simple text input:
```
<input class="simple-input" type="password" name="password" />
```

Simple checkboxes and radio buttons:
```
<label class="simple-box">
    <input type="radio" name="favorite_pet" value="Cats"> Cats 
</label> 
```

Simple fieldset:
```
<fieldset class="simple-fieldset">      
  <legend>What is your favorite pet?</legend>    
  ...
</fieldset>
```

Simple hero section:
```
<div class="simple-hero">
    <div class="simple-hero__content">
        <h1>This is a hero</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit....</p>
        <a href="#" class="simple-button simple-button--primary">Call to Action</a>
    </div>
</div>
```

Simple navigation:
```
<div class="simple-navigation">
    <ul class="">
        <li>Menu Item 1</li>
        <li>Menu Item 2</li>
        <li>Menu Item 3</li>
        <li class="highlighted">Menu Item 4</li>
    </ul>
</div>
```
