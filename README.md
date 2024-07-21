# FSWDT13
DAY13
<!DOCTYPE html>
<html>
    <head>
        <title>Media Queries Github basics and project</title>
        <link rel="stylesheet" href="./day13.css">
    </head>
    <body>
        <h3>hey guys today we are going to deal abou the media queries session,gitub basics and project </h3>
        <p>hey its paragraph</p>
    </body>
</html>
/* screen size is in the range of 800-1200 */
/* @media only screen and (max-width:1200px){
    h3{
        color: yellow;
        font-size: 25px;
    }
    p{
        color: green;
        font-size: 14px;
    }
} */
/* screen size is in the range of 400-800 */
/* @media only screen and (max-width:800px){
    h3{
        color: red;
        font-size: 12px;
    }
    p{
        color: violet;
        font-size: 10px;
    }
} */
/* screen size is in the range of 0-400 */
@media only screen and (min-width:400px){
    h3{
        color: blue;
        font-size: 20px;
    }
    p{
        color: orangered;
        font-size: 8px;
    }
    /* max-width: 
    eg:max-width 400px(screen size <=400px); */
    /* min-width: 
    eg:min-width 400px(screen size >=400px); */
}
@media only screen and (min-width:400px){
    h3{
        color: red;
        font-size: 20px;
    }
    p{
        color: yellow;
        font-size: 8px;
    }
}
