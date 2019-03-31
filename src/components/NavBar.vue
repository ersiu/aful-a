<template>
    <div>
        <!-- NAVBAR WITH RESPONSIVE TOGGLE -->
        <nav class="navbar navbar-expand-sm navbar-dark bg-dark fixed-top">
            <div class="container">
                <a class="navbar-brand" href="#">Looper</a>
                <button class="navbar-toggler" data-toggle="collapse" data-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
          </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item">
                            <a class="nav-link" href="#home-section">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#explore-head-section">Explore</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#create-head-section">Create</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#share-head-section">Share</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
    export default {
        name: 'theNavBar'
    }
</script>

<style scoped>
  .navbar {
      border-bottom: #008ed6 3px solid;
      opacity: 0.8;
  }

</style>