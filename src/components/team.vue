<template>
    <div class="container-fluid">
        <section style="box-shadow: 0 5px 6px -3px rgba(0, 0, 0, 0.4); font-weight: lighter;" class="hero is-medium">
            <!-- Hero head: will stick at the top -->
            <div class="hero-head">
                <navbar/>
            </div>

            <!-- Hero content: will be in the middle -->
            <div class="hero-body">
                <div class="container has-text-left">
                    <img style="width: 200px;" id="team-img" src="../assets/logos/logo-white.svg" alt="">
                    <p class="title">    
                        Meet the Team
                    </p>
                </div>
            </div>
            <!-- Hero footer: will stick at the bottom -->
            <div class="hero-foot">
                  
            </div>
        </section>
        <section style="margin-top: 50px" class="hero is-light">
            <!-- Hero content: will be in the middle -->
            <div class="hero-body">
                <div class="container">
                    <div style="font-size: 14px" class=" has-text-justified">    
                        <p> Google is known all around the world. Everyone is 'googling', 
                            checking on 'maps' and communicating in 'gmail'. For simple 
                            users, they are services that just works, but not for us. 
                            Developers see much more: APIs, scalability issues, complex technology stacks. 
                            And that is what GDG is about.
                        </p>
                        <br>
                        <p>
                            <a href="">GDG North CentralDevFest</a> - is open and volunteer geek community who create exciting 
                            projects and share experience about Google technologies with a passion.
                        </p>
                        <br>
                        <p>
                            Our goal is to organize space to connect the best industry experts with our community audience to boost development of IT in Nigeria.  
                        </p>

                    </div>
                </div>
            </div>
        </section>
        <section class="team-members-wrapper has-text-centered content">
            <div class="columns">
                <div class="column ">
                    <div class="member-card">
                        <br>
                        <div class="member-card-image">
                        <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/people/abdullahi.jpeg">
                            </figure> 
                        </div>
                        <h1 style="font-size: 24px">Abdullahi Aliyu</h1>
                        <img class="gdg-logo" src="../assets/logos/gdg-logo.png" alt="">
                        <p>Lafia, Nigeria</p>
                        <p>
                            <a  style="color: #4d4d4d; padding:5px" target="_blank" href="https://github.com/abbaxee">
                                <b-icon
                                    pack="fab"
                                    icon="github"
                                    size="is-small">
                                </b-icon>
                            </a>
                            <a class="is-info" style="padding:5px" data-social-network="Twitter" 
                            target="_blank" href="https://twitter.com/abba_xee">
                                <b-icon
                                    icon="twitter"
                                    size="is-small">
                                </b-icon>
                            </a>
                        </p>
                        <br>
                    </div>    
                </div>
                <div class="column ">
                    <div class="member-card">
                        <br>
                        <div class="member-card-image">
                        <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/people/abdullahi.jpeg">
                            </figure> 
                        </div>
                        <h1 style="font-size: 24px">Abdullahi Aliyu</h1>
                        <img class="gdg-logo" src="../assets/logos/gdg-logo.png" alt="">
                        <p>Abuja, Nigeria</p>
                        <p>
                            <a  style="color: #4d4d4d; padding:5px" target="_blank" href="https://github.com/abbaxee">
                                <b-icon
                                    pack="fab"
                                    icon="github"
                                    size="is-small">
                                </b-icon>
                            </a>
                        <a  style="color: #3B5998; padding:5px" data-social-network="Facebook"
                        target="_blank" href="https://web.facebook.com/Abbarious">
                            <b-icon
                                icon="facebook"
                                size="is-small">
                            </b-icon>
                        </a>
                        <a class="is-info" style="padding:5px" data-social-network="Twitter" 
                        target="_blank" href="https://twitter.com/abba_xee">
                            <b-icon
                                icon="twitter"
                                size="is-small">
                            </b-icon>
                        </a>
                        </p>
                        <br>
                    </div>    
                </div>
                <div class="column ">
                    <div class="member-card">
                        <br>
                        <div class="member-card-image">
                        <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/people/abdullahi.jpeg">
                            </figure> 
                        </div>
                        <h1 style="font-size: 24px">Abdullahi Aliyu</h1>
                        <img class="gdg-logo" src="../assets/logos/gdg-logo.png" alt="">
                        <p>Abuja, Nigeria</p>
                        <p>
                            <a  style="color: #4d4d4d; padding:5px" target="_blank" href="https://github.com/abbaxee">
                                <b-icon
                                    pack="fab"
                                    icon="github"
                                    size="is-small">
                                </b-icon>
                            </a>
                        <a  style="color: #3B5998; padding:5px" data-social-network="Facebook"
                        target="_blank" href="https://web.facebook.com/Abbarious">
                            <b-icon
                                icon="facebook"
                                size="is-small">
                            </b-icon>
                        </a>
                        <a class="is-info" style="padding:5px" data-social-network="Twitter" 
                        target="_blank" href="https://twitter.com/abba_xee">
                            <b-icon
                                icon="twitter"
                                size="is-small">
                            </b-icon>
                        </a>
                        </p>
                        <br>
                    </div>    
                </div>
                <div class="column ">
                    <div class="member-card">
                        <br>
                        <div class="member-card-image">
                        <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/people/abdullahi.jpeg">
                            </figure> 
                        </div>
                        <h1 style="font-size: 24px">Abdullahi Aliyu</h1>
                        <img class="gdg-logo" src="../assets/logos/gdg-logo.png" alt="">
                        <p>Abuja, Nigeria</p>
                        <p>
                            <a  style="color: #4d4d4d; padding:5px" target="_blank" href="https://github.com/abbaxee">
                                <b-icon
                                    pack="fab"
                                    icon="github"
                                    size="is-small">
                                </b-icon>
                            </a>
                        <a  style="color: #3B5998; padding:5px" data-social-network="Facebook"
                        target="_blank" href="https://web.facebook.com/Abbarious">
                            <b-icon
                                icon="facebook"
                                size="is-small">
                            </b-icon>
                        </a>
                        <a class="is-info" style="padding:5px" data-social-network="Twitter" 
                        target="_blank" href="https://twitter.com/abba_xee">
                            <b-icon
                                icon="twitter"
                                size="is-small">
                            </b-icon>
                        </a>
                        </p>
                        <br>
                    </div>    
                </div>   
            </div>
            <div class="columns">
                <div class="column ">
                    <div class="member-card">
                        <br>
                        <div class="member-card-image">
                        <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/people/abdullahi.jpeg">
                            </figure> 
                        </div>
                        <h1 style="font-size: 24px">Abdullahi Aliyu</h1>
                        <img class="gdg-logo" src="../assets/logos/gdg-logo.png" alt="">
                        <p>Abuja, Nigeria</p>
                        <p>
                            <a  style="color: #4d4d4d; padding:5px" target="_blank" href="https://github.com/abbaxee">
                                <b-icon
                                    pack="fab"
                                    icon="github"
                                    size="is-small">
                                </b-icon>
                            </a>
                        <a  style="color: #3B5998; padding:5px" data-social-network="Facebook"
                        target="_blank" href="https://web.facebook.com/Abbarious">
                            <b-icon
                                icon="facebook"
                                size="is-small">
                            </b-icon>
                        </a>
                        <a class="is-info" style="padding:5px" data-social-network="Twitter" 
                        target="_blank" href="https://twitter.com/abba_xee">
                            <b-icon
                                icon="twitter"
                                size="is-small">
                            </b-icon>
                        </a>
                        </p>
                        <br>
                    </div>    
                </div>
                <div class="column ">
                    <div class="member-card">
                        <br>
                        <div class="member-card-image">
                        <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/people/abdullahi.jpeg">
                            </figure> 
                        </div>
                        <h1 style="font-size: 24px">Abdullahi Aliyu</h1>
                        <img class="gdg-logo" src="../assets/logos/gdg-logo.png" alt="">
                        <p>Abuja, Nigeria</p>
                        <p>
                            <a  style="color: #4d4d4d; padding:5px" target="_blank" href="https://github.com/abbaxee">
                                <b-icon
                                    pack="fab"
                                    icon="github"
                                    size="is-small">
                                </b-icon>
                            </a>
                        <a  style="color: #3B5998; padding:5px" data-social-network="Facebook"
                        target="_blank" href="https://web.facebook.com/Abbarious">
                            <b-icon
                                icon="facebook"
                                size="is-small">
                            </b-icon>
                        </a>
                        <a class="is-info" style="padding:5px" data-social-network="Twitter" 
                        target="_blank" href="https://twitter.com/abba_xee">
                            <b-icon
                                icon="twitter"
                                size="is-small">
                            </b-icon>
                        </a>
                        </p>
                        <br>
                    </div>    
                </div>
                <div class="column ">
                    <div class="member-card">
                        <br>
                        <div class="member-card-image">
                        <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/people/abdullahi.jpeg">
                            </figure> 
                        </div>
                        <h1 style="font-size: 24px">Abdullahi Aliyu</h1>
                        <img class="gdg-logo" src="../assets/logos/gdg-logo.png" alt="">
                        <p>Abuja, Nigeria</p>
                        <p>
                            <a  style="color: #4d4d4d; padding:5px" target="_blank" href="https://github.com/abbaxee">
                                <b-icon
                                    pack="fab"
                                    icon="github"
                                    size="is-small">
                                </b-icon>
                            </a>
                        <a  style="color: #3B5998; padding:5px" data-social-network="Facebook"
                        target="_blank" href="https://web.facebook.com/Abbarious">
                            <b-icon
                                icon="facebook"
                                size="is-small">
                            </b-icon>
                        </a>
                        <a class="is-info" style="padding:5px" data-social-network="Twitter" 
                        target="_blank" href="https://twitter.com/abba_xee">
                            <b-icon
                                icon="twitter"
                                size="is-small">
                            </b-icon>
                        </a>
                        </p>
                        <br>
                    </div>    
                </div>
                <div class="column ">
                    <div class="member-card">
                        <br>
                        <div class="member-card-image">
                        <figure class="image is-128x128">
                                <img class="is-rounded" src="../assets/people/abdullahi.jpeg">
                            </figure> 
                        </div>
                        <h1 style="font-size: 24px">Abdullahi Aliyu</h1>
                        <img class="gdg-logo" src="../assets/logos/gdg-logo.png" alt="">
                        <p>Abuja, Nigeria</p>
                        <p>
                            <a  style="color: #4d4d4d; padding:5px" target="_blank" href="https://github.com/abbaxee">
                                <b-icon
                                    pack="fab"
                                    icon="github"
                                    size="is-small">
                                </b-icon>
                            </a>
                        <a  style="color: #3B5998; padding:5px" data-social-network="Facebook"
                        target="_blank" href="https://web.facebook.com/Abbarious">
                            <b-icon
                                icon="facebook"
                                size="is-small">
                            </b-icon>
                        </a>
                        <a class="is-info" style="padding:5px" data-social-network="Twitter" 
                        target="_blank" href="https://twitter.com/abba_xee">
                            <b-icon
                                icon="twitter"
                                size="is-small">
                            </b-icon>
                        </a>
                        </p>
                        <br>
                    </div>    
                </div>   
            </div>
        </section>
        <div>
            <Pagefooter/>
        </div>
    </div>
    
</template>

<script>
import Navbar from "./navbar";
import Pagefooter from "./footer";
export default {
    name: "team",
    data(){
        return {
            msg: "Hello Team"
        }
    },
    components : {
        Navbar,
        Pagefooter
    }
}
</script>
