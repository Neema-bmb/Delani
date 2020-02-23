# ANDIA STUDIOS
### 19/2/2020
#### By Neema Shiramba
## Description
## Behaviour Based Development

### Home page
I added the logo using the link method show below, then typed in the content using the appropriate sizes of text as shown.

```
  <div class="back">
                    <div class="logo"><img src="IP3-master/assets/logo/logo.png"></div><br><br>
                    <H1>WELCOME</H1>
                    <h1>TO DELANI STUDIO</h1>
                    <p>AMAZING PEOPLE ARE MAKING AMAZING DESIGNS IN FUN ENVIRONMENT</p><br><br><br><br><br><br>
                    <img src="IP3-master/assets/mouse_click.png">
                </div><br><br>
```
i then added the background image using css.

### About Us and Services
This sections were simple to create and all that was needed was to place them into containers and style them using css.

### Icons
The icons were created to be able to toggle when clicked. To do this by 

```
<div class="container-fluid">
                <div class="row">
                    <div class="col-md-4 col-xs-4">
                        <div id="design"><img src="/IP3-master/assets/services_icons/design_icon.png">
                            <h6>DESIGN</h6>
                        </div>
                        <div id="content">
                            <h6><b>DESIGN</b></h6>
                            <p>
                                Our design practice offers a full range of services including brand strategy, interaction and
                                visual design and user experience testing.
                                Throughout your project, our designers create and implement visual design and workflows, solicit
                                user feedback and work with you to make sure what gets built is what is needed.
                            </p>
                        </div>
                    </div>
                    <div class="col-md-4 col-xs-4">
                        <div id="dev"><img src="IP3-master/assets/services_icons/dev_icon.png">
                            <h6>DEVELOPMENT</h6>
                        </div>
                        <div id="dev-content">
                            <h6><b>DEVELOPMENT</b></h6>
                            <p>
                                All engineers are fluent in the latest enterprise, mobile and web development technologies.
                                They collaborate with your team to write, and improve code on a daily basis, using proven
                                practices such as test-driven development and pair programming.
                            </p>
                        </div>
                    </div>
                    <div class="col-md-4 col-xs-4">
                        <div id="product"><img src="IP3-master/assets/services_icons/product_icon.png">
                            <h6>PRODUCT MANAGEMENT</h6>
                        </div>
                        <div id="prod-content">
                            <h6><b>PRODUCT MANAGEMENT</b></h6>
                            <p>
                                Planning and development is iterative. Because we are constantly coding and testing, the
                                products we build are always ready to go live.
                                This iterative process allows for changes as business requirements evolve.
                            </p>
                        </div>
                    </div>
                </div>
```
then add the following Javascript to make it function as wanted, using the classes that were assigned above.

```
  $("div#design").click(function() {
      $("div#content").toggle();
      $("div#design").toggle();
    });
    $("div#content").click(function() {
      $("div#content").toggle();
      $("div#design").toggle();
    });
    $("div#dev").click(function() {
      $("div#dev-content").toggle();
      $("div#dev").toggle();
    });
    $("div#dev-content").click(function() {
      $("div#dev-content").toggle();
      $("div#dev").toggle();
    });
    $("div#product").click(function() {
      $("div#prod-content").toggle();
      $("div#product").toggle();
    });
    $("div#prod-content").click(function() {
      $("div#prod-content").toggle();
     $("div#product").toggle();
    });
```


## Known Bugs
If you find any issues in the code feel free to [click here](https://neema-bmb.github.io/Delani/)

### Technologies Used
I used:
*HTML- write the content of page
*Bootstrap & CSS- for styling
*jQuery & Javascript- to make the page responsive

## Contact me on: neemashiramba@gmail.com
{I encourage anyone who has any contribution to make to this code to improve it do so. 
Live link:}


### License
App is licenced by [MIT.licensing](LICENCE.txt)