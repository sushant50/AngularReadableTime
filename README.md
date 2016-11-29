# AngularReadableTime
Clone the Javascript file and include it in your html page. Inject AngularReadableTime in your app.js and use it in your HTML as a filter. 

Example-
~~~~
     var app = angular.module('priApp',
               [ 'ngRoute', 'ngResource', 'ui.bootstrap','toastr','#                      AngularReadableTime','appcontroller','TagCtrl','xeditable','directives']);
    
    <div class="row ipAddressdetails">
    <div class="col-lg-12 col-md-12 text-center">
    <span class="glyphicon glyphicon-time"></span> {{init.freeswitch_status[port1].uptime | AngularReadableTime }}
    </div>
    </div>
    
~~~~
