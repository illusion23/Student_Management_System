<template>
    <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        Master Data
        </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <router-link to='/admin'  class="dropdown-item"><i class="fa fa-home" aria-hidden="true"></i> Dashboard</router-link>
            <router-link to='/student'  class="dropdown-item"><i class="fa fa-user-graduate" aria-hidden="true"></i> Student</router-link>
            <router-link to='/class'  class="dropdown-item"><i class="fa fa-users" aria-hidden="true"></i> Class</router-link>
            <router-link to='/class'  class="dropdown-item"><i class="fa fa-layer-group" aria-hidden="true"></i> Level</router-link>
            <router-link to='/class'  class="dropdown-item"><i class="fa fa-user-tie" aria-hidden="true"></i> Teacher</router-link>


            </div>
    </li>
</template>

<script>
export default {
    mounted(){
        console.log('component mounted !');
    }
}
</script>
