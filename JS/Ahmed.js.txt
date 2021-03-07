                                // j query
$(document).ready(function()
        {
            $("form").fadeOut(2000).slideDown(2000);         // slide down the form after hodden it
            $("h1").animate({                               
                fontSize:'40px'
                    },1500);
            $("h1").animate({
                fontSize:'hide',
                    },1200);
           $("h1").animate({
                fontSize:'show'
                    },1500);
        });

var DegreeChair = new Array("Q","K","H","L");
    console.log(DegreeChair.length);
    console.log(DegreeChair);
    
    var user,q,k,h,l,x,n;
    q=300; k=330; h=400; l=430;
    user = window.prompt('Please Enter your Name :','');
    
     n = document.getElementById("select").value;
    console.log(n);
    
            x = document.getElementById("type").value;
            
    function myFunction(x) {
            if( x === "Q")
            {
                document.getElementById("C1").innerHTML = x;
                alert(user +' >>> You choose chair At ' + x + " Degree By : " + q +" $ ");
            }
            else if(x === "K")
            {
                document.getElementById("C2").innerHTML = x;
                alert(user +' >>> You choose chair At ' + x + " Degree By : " + k +" $ " );
            }
            else if(x === "H")
            {
                document.getElementById("C3").innerHTML = x;
                alert(user +' >>> You choose chair At ' + x + " Degree By : " + h +" $ " );
            }
            else if(x === "L")
            {
                document.getElementById("C4").innerHTML = x;
                alert(user +' >>> You choose chair At ' + x + " Degree By : " + l +" $ " );
            }
        }
    myFunction(x);
    