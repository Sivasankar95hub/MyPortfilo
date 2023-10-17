# MyPortfolio
html{
    scroll-behavior: smooth;
}
#s1{
    border: none;
}
#img1 {
    border-radius: 60%;
    border-style: solid;
    width: 250px;
}

.one {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 50px;
}

.three {
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    color: rgb(174, 0, 255);
    font-size:17px
}
.container1 {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40vh;
}
@media(max-width:800px){
    .container1{
        flex-direction: column;
        height:100vh;
    }
}
.dot1 {
    width: 150px;
    height: 150px;
    background-color:orange;
    border-radius: 50%;
    margin: 0 10px;
    text-align: center;
    line-height: 150px;
}

.dot1:hover {
    cursor: pointer;
    background-color: ghostwhite;
    transition: 0.5s;
}

.dot2 {
    width: 150px;
    height: 150px;
    background-color:red;
    border-radius: 50%;
    margin: 0 10px;
    text-align: center;
    line-height: 150px;

}

.dot2:hover {
    cursor: pointer;
    background-color: ghostwhite;
    transition: 0.5s;

}

.dot3 {
    width: 150px;
    height: 150px;
    background-color:aqua;
    border-radius: 50%;
    margin: 0 10px;
    text-align: center;
    line-height: 150px;
}

.dot3:hover {
    cursor: pointer;
    background-color: ghostwhite;
    transition: 0.5s;

}

.Resume {
    text-align: center;
    padding-top: 10px;
    color: rgb(39, 38, 38);
}

.Intern {
    text-align: center;
    padding-top: 50px;
    color: rgb(39, 38, 38);
}

.Project {
    text-align: center;
    padding-top: 50px;
    color: rgb(39, 38, 38);
}
