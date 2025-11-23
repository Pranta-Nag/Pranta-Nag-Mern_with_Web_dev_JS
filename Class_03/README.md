******** CSS ******
    Styling Tool
-----------------------
CSS = Cascading Style Sheet

Color => Changes the text color

# Why not inline CSS?
    1. Specificity issue
    2. Not maintaiable
    3. Can't use pseudo classes and elements

 <!-- Inline CSS  (1st way to write CSS)
 <body style="background-color:darkslategray;color: aquamarine; text-align: center;">

    <div style="background-color: antiquewhite; color: black;">
        My name is Pranta Nag
    </div>

</body>  -->

  <!-- 2nd way to write CSS
    <style>
        body {
            background-color: darkslategray;
            color: aquamarine;
            text-align: center;
        }

        div {
            background-color: bisque;
            color: black;
        }
    </style> -->

3rd way => create another folder on css

CSS Selector ...........
body {}
=> body{

}

class="abc"{}      ; use for group of class
=> .abc{

}

id="abc"{}      ; use for single part
=> #abc{

}


<div> => Full space
<span> => Just set content space

inline element => do not work column

******* Box Model *******

    #BOX
    Border -> Padding -> Content 

    #Margin
    Box -> Margin -> Box