 Helloo.world
Just trying out github for the first time.. pretty excited about it!

#important links and commands
=> Database design:
   http://ondras.zarovi.cz/sql/demo/
   
=> setting password for mysql.
	set password for 'root'@'localhost'= password('mysql');

=> Laravel Project creation.
   composer create-project laravel/laravel project-name --prefer-dist
 
=> Laravel cheat sheet
	http://cheats.jesse-obrien.ca/
=> UI libraries : UIbox http://www.uibox.in/item/50


# product display.
http://tympanus.net/Development/MockupSlideshow/index4.html

http://www.freshdesignweb.com/jquery-image-slider-slideshow.html

# atom snippets


'.source.js':
  'Controller action':
    'prefix': 'act'
    'body': """
            $1:function(req,res,next){
               $2
            }
            """
  'Describe block' :
    'prefix' : 'tdesc'
    'body' : """
             describe("$1",function(){
                  $2
               });
             """
  'Test block' :
    'prefix' : 'tit'
    'body' : """
             it("$1",function(done){
                $2
             });
             """
  'Anonymous function' :
    'prefix' : 'af'
    'body' : """
            function($1){
              $2
            }
             """
  'Module exports' :
    'prefix' : 'me'
    'body' : """
            module.exports = {
              $1
            };
             """
  'Api service function template' :
    'prefix' : 'sf'
    'body' : """
              $1 : function(data){
                $2
              }
             """
  'Promise catch block' :
    'prefix' : 'pc'
    'body' : """
                .catch(function(err){

                });
             """
  'Promise then block' :
    'prefix' : 'pt'
    'body' : """
                .then(function($1){
                    $2
                })
             """
  'Test Request block' :
    'prefix' : 'treq'
    'body' : """
              	  $1.send({$2}).
            			expect($3).
            			end(function(err,res){

            				done();
            			});
             """

