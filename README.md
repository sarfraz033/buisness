<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buisness</title>
<style>
  
  /* common style starts here */
body{
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    min-width: 752px;
    margin: 0;
    padding: 0;
    color: rgb(29, 29, 29);
    background-color: #ffffff;
}
::selection{
    color: white;
    background-color: #5468db;
}
a{
    color: #5468db;
}
.ads{
    background-color: #e4e4e4;
    padding: 10px;
    border-radius: 7px;
    font-size: 11px;
}
/* common style ends here */


.navBar{
    background-color: #5468db;
    display: flex;
    color: white;
    position: sticky;
    top: 0;
}
.webTitle{
    width: 200px;
    text-align: center;
    padding: 16px;
    font-size: 30px;
    box-shadow: 0px 0px 10px black;
}
nav{
    display: flex;
    /* width: 85%; */
}
nav ul{
    display: flex;
}
nav ul li{
    list-style: none;
    display: flex;
    padding: 10px 20px;
}
nav ul li a{
    color: white;
    text-decoration: none;
}
.sections{
    /* padding: 10px; */
    display: flex;
}
.left{
    width: 220px;
    /* height: 100vh; */
    /* background-color: red; */
    box-shadow: 0px 0px 5px black;
    font-size: 17px;
    /* text-align: center; */
    margin-right: 10px;
}
.left ul li{
    list-style: none;
    padding: 10px 0px;
}
.left ul li a{
    text-decoration: none;
}
.center{
    width: 65%;
    padding: 16px;
    /* background-color: white; */
}
.right{
    width: 20%;
    box-shadow: 0px 0px 5px black;
    margin-left: 10px;
    padding: 10px 20px;

}


@media only screen and (max-width:1300px){

    .webTitle{
        width: 170px;
    }

}


@media only screen and (max-width:752px){

    .webTitle{
        width: 145px;
    }

}
  
  </style>
</head>
<body>

    <div class="navBar">
        <div class="webTitle">
            Buisness
        </div>
        <nav class="webNav">
            <ul>
                <li> <a href="#">Home</a> </li>
                <li> <a href="#">Our Services</a> </li>
                <li> <a href="#">About Us</a> </li>
                <li> <a href="#">Contact Us</a> </li>
            </ul>
        </nav>
    </div>
    <div class="sections">
        <section class="left">
            <ul>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
                <li><a href="#">Click here</a></li>
            </ul>
        </section>

        <section class="center">
         Lorem ipsum dolor sit amet, consectetur adipisicing elit. Praesentium impedit et deserunt assumenda sapiente reprehenderit, tempore fuga, quia vitae sed nihil dicta. Sed nulla ipsum dolorum eum quae numquam quidem, vel, ad fugiat laboriosam inventore necessitatibus! Quo necessitatibus itaque odit, quam provident labore dolorum, explicabo deleniti ex accusamus blanditiis voluptatem veniam. Quibusdam consequatur a aut rerum veniam. Nisi dolorem corporis voluptatum! Magni officiis provident dicta eum, assumenda amet maxime hic nesciunt reiciendis iste, fugiat unde. Nobis eum assumenda veniam neque. Placeat dolorum mollitia reiciendis expedita voluptate quisquam voluptatibus unde recusandae voluptatem accusamus voluptatum ipsa eveniet quis, fugiat qui? Asperiores, eum.
        </section>

        <section class="right">
            <center>
                <!-- <h2>Advertisements</h2> -->
            </center>
            <p class="ads">
         Lorem ipsum dolor sit amet, consectetur adipisicing elit. Praesentium impedit et deserunt assumenda sapiente reprehenderit, tempore fuga, quia vitae sed nihil dicta. Sed nulla ipsum dolorum eum quae numquam quidem, vel, ad fugiat laboriosam inventore necessitatibus! Quo necessitatibus itaque odit, quam provident labore dolorum, explicabo deleniti ex accusamus blanditiis voluptatem veniam. Quibusdam consequatur a aut rerum veniam. Nisi dolorem corporis voluptatum! Magni officiis provident dicta eum, assumenda amet maxime hic nesciunt reiciendis iste, fugiat unde. Nobis eum assumenda veniam neque. Placeat dolorum mollitia reiciendis expedita voluptate quisquam voluptatibus unde recusandae voluptatem accusamus voluptatum ipsa eveniet quis, fugiat qui? Asperiores, eum.
        </p>
        </section>

    </div>
</body>
</html> 
