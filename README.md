# leadership-directory
A directory that lists the key people in your organization's departments will help your visitors find the right person to contact easily and ask questions directly. With Bootstrap's table structure, you can easily create a leadership directory with people's names and their contact information.

## Tutorial
For detailed instruction's, view Solodev's [How to Create a Leadership Directory on Your Website](http://www.solodev.com/blog/web-design/how-to-create-a-leadership-directory-on-your-website.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/pfzcjat4/).

## HTML
The tutorial contains the following basic HTML markup.

```
   <div class="container">
        <div class="row">
          <div class="col-md-12 ct-content mt-5 mb-5">
            <p>At LunarXP, we’re dreamers and explorers. LunarXP has a passionate leadership team that's dedicated to make a better tomorrow for all of us. Any questions you may have can be answered and are welcomed by the leadership team members listed below.</p>
    
            <div class="table-responsive">
              <table class="table table-stripped table-bordered">
                <thead>
                  <tr>
                    <th scope="col">Name</th>
                    <th scope="col">Title</th>
                    <th scope="col">Phone Number</th>
                    <th scope="col">Email</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <th scope="row">Veronica Gutierrez, MD</th>
                    <th>Astromedicine practitioner</th>
                    <th><a href="tel:8001237656">800.123.7656</a></th>
                    <th><a href="mailto:veronica.Gutierrez@lunarxp.com">veronica.Gutierrez@lunarxp.com</a></th>
                  </tr>
                  <tr>
                    <th scope="row">Capt. Nathan Patrick</th>
                    <th>VALKYRIE-1 Pilot</th>
                    <th><a href="tel:8001237656">800.123.7656</a></th>
                    <th><a href="mailto:nathan.patrick@lunarxp.com">nathan.patrick@lunarxp.com</a></th>
                  </tr>
                  <tr>
                    <th scope="row">Jacquelyn Li</th>
                    <th>Lunar Life Sciences</th>
                    <th><a href="tel:8001237656">800.123.7656</a></th>
                    <th><a href="mailto:jacquelyn.drake@lunarxp.com">jacquelyn.drake@lunarxp.com</a></th>
                  </tr>
                  <tr>
                    <th scope="row">Cmdr. Adam Paul</th>
                    <th>XP-1 BASE OPERATIONS</th>
                    <th><a href="tel:8001237656">800.123.7656</a></th>
                    <th><a href="mailto:adam.paul@lunarxp.com">adam.paul@lunarxp.com</a></th>
                  </tr>
                </tbody>
              </table>
            </div>
            <div>
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
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```