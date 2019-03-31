<template>
    <div>
        <!-- HOME SECTION -->
        <header id="home-section">
            <div class="dark-overlay">
                <div class="home-inner container">
                    <div class="row">
                        <div class="col-lg-8 d-none d-lg-block">
                            <h1 class="display-4">Build your <strong>business online</strong> and gain revenue <strong>profit</strong>
                            </h1>
    
                            <div class="d-flex">
                                <div class="p-4 align-self-start">
                                    <i class="fas fa-check fa-2x"></i>
                                </div>
                                <div class="p-4 align-self-end">
                                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Excepturi, error sapiente. Amet cum adipisci aspernatur!
                                </div>
                            </div>
    
                            <div class="d-flex">
                                <div class="p-4 align-self-start">
                                    <i class="fas fa-check fa-2x"></i>
                                </div>
                                <div class="p-4 align-self-end">
                                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Excepturi, error sapiente. Amet cum adipisci aspernatur!
                                </div>
                            </div>
    
                            <div class="d-flex">
                                <div class="p-4 align-self-start">
                                    <i class="fas fa-check fa-2x"></i>
                                </div>
                                <div class="p-4 align-self-end">
                                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Excepturi, error sapiente. Amet cum adipisci aspernatur!
                                </div>
                            </div>
    
    
                        </div>
    
                        <div class="col-lg-4">
                            <div class="card bg-primary text-center card-form">
                                <div class="card-body">
                                    <h3>Sign Up Today</h3>
                                    <p>Please fill out this form to register</p>
                                    <form>
                                        <div class="form-group">
                                            <input type="text" class="form-control form-control-lg" placeholder="Username">
                                        </div>
                                        <div class="form-group">
                                            <input type="email" class="form-control form-control-lg" placeholder="Email">
                                        </div>
                                        <div class="form-group">
                                            <input type="password" class="form-control form-control-lg" placeholder="Password">
                                        </div>
                                        <div class="form-group">
                                            <input type="password" class="form-control form-control-lg" placeholder="Confirm Password">
                                        </div>
                                        <input type="submit" class="btn btn-outline-light btn-block">
                                    </form>
                                </div>
                            </div>
                        </div>
    
                    </div>
                </div>
            </div>
        </header>
    </div>
</template>

<script>
    export default {
        name: 'homeSection'
    };
</script>

<style scoped>
    #home-section {
        background: url(../assets/img/home5.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        background-attachment: fixed;
        min-height: 800px;
        color: #ffffff;
        /* text-shadow: -1px -1px 0 hsl(280, 70%, 35%), -2px -2px 1px hsl(280, 70%, 35%); */
        text-shadow: 3px 3px 3px black;
    }
    
    #home-section .dark-overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        min-height: 800px;
        background: rgba(0, 0, 0, 0.3)
    }
    
    #home-section .home-inner {
        padding-top: 150px;
    }


</style>