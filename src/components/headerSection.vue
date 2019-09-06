<template>
    <div class="firstform">
        <div class="header">
            <div class="container">
                <ul>
                    <li><a class="#" href="#home">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Portfolio</a></li>
                    <li style="float:right"><a class="active" href="#">Contact</a></li>
                </ul>
            </div>
        </div>   
    </div>
</template>

<script>
    export default {
    
    }
</script>

<style>
    .header {
        background-color:black;
    }
    
    ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color:black;
    }
    
    li {
        float: left;
    }
    
    li a {
        display: block;
        color: white;
        text-align: center;
        padding: 10px 12px;
    }
    
    li a:hover {
        background-color:gray;
    }
    
    li.style {
        float: right;
    }
    
    .form {
        text-align: left;
    }
</style>
