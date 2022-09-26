<template>
    <div class = "main-container">
        <div class="container-one">
           <div class="profile">
                <img src = "../assets/rock.jpg" alt = "">
                <h3> Travis Quigg</h3>
                <p> Software Developer</p>
           </div>
           <div class = "social-links">
                
                    <div class = "link">
                        <a href = ""> <img class = "git" src = "../assets/git.png" alt =""> </a>  
                    </div>
                
                
                    <div class = "link">
                        <a href = ""> <img class = "link" src = "../assets/linked.png" alt = ""> </a>
                        
                    </div>
                
                
                    <div class = "link">
                        <a href = ""><img src = "../assets/ing.png" alt = ""></a>
                    
                    </div>
               

            </div>
        </div>
        <div class = "container-two">
            <div class = "about-me">
                <h1>About Me</h1>
                <p> I am an enthusiastic driven individual that seeks out all challenges whether 
                    it  be pushing my physical or mental limits. I have extensive knowledge of web development -
                    both frontend and backend. Utilizing multiple stacks and also know Ai and Data Analysis. This website is built using Vue, Django,
                    and uploaded via vercel.</p>
            </div>

            <div class = "me">
                <h1>Technologies and Experience</h1>
            </div>
        
            <div class="button-container">
                <div class = "projects-button">
                    <a href = "Projects">projects</a>
                </div>
                <div class = "projects-button">
                    <a href = ""> My Resume </a>
                </div>


            </div>
        </div>
    </div>
</template>

<script>
    export default{

    }
</script>
<style scoped>
    .social-links{
        display: flex;
        flex-direction: row;
        justify-content: center;
    }
    img{
      height: 5rem;  
    }

    
    .main-container{
        display: flex;
        flex-direction: row;
        background-color: #122620;
        border-radius: 27%;
    }
    .link{
        height:4rem;
    }
   

    .container-one{
        background-color: #B68D40;
        padding: 2.5%;
        width:30%;
    }
    .profile img{
        height:9rem;
        border-radius: 50%;
    }

    .container-two{
        background-color: #D6AD60;
        margin: 1.5%;
        width:70%;
        border-radius: 25px;
    }
    .about-me{
        text-align:left;
    }
    .button-container{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        margin-top: 5%;
    }
    .projects-button{
        background-color: #F4EbD0;
        margin: 5px;
        padding: 7.5px;
        border-radius: 15px;
    }
    
    .projects-button a{
        text-decoration: none;
        color: grey;
    }
</style>