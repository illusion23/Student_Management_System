<template>
    <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        Operations
        </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <router-link to='/admin'  class="dropdown-item"><i class="fa fa-home" aria-hidden="true"></i> Dashboard</router-link>


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
