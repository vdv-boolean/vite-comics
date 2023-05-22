<script>
export default {
    data () {
    
    return {
        navbaritems:[
            
            {
                name: "CHARACTERS",
                src: "#",
                active: false,
            },
            {
                name: "COMICS",
                src: "#",
                active: false,
            },
            {
                name: "MOVIES",
                src: "#",
                active: false,
            },
            {
                name: "TV",
                src: "#",
                active: false,
            },
            {
                name: "GAMES",
                src: "#",
                active: false,
            },
            {
                name: "COLLECTIBLES",
                src: "#",
                active: false,
            },
            {
                name: "VIDEOS",
                src: "#",
                active: false,
            },
            {
                name: "FANS",
                src: "#",
                active: false,
            },
            {
                name: "NEWS",
                src: "#",
                active: false,
            },
            {
                name: "SHOP",
                src: "#",
                active: false,
            },
        ]
    }
}
}
</script>



<template>
  <nav>
      <ul>
        <li v-for="menuItem in navbaritems" :key="menuItem.name">
			<a :href="menuItem.src">{{ menuItem.name }}</a>
		</li>
      </ul>
    </nav>
</template>



<style scoped>

    nav{
        height: 100%;
    }
    
    ul{
        gap: 1em;
        list-style: none;
        height: 100%;
        display: flex;
    }

    li{
        height: 100%;
        padding: .5em;
        font-size: 14px;
    }
  
    a{
        text-decoration: none;
        color: black;
    }
</style>