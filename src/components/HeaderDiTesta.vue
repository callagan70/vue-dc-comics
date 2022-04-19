<template>
  <div class="testa">
    <div>
      <img src="../assets/img/dc-logo.png" alt="Logo Dc">
    </div>
    
    <div class="lista">
        <ul>
          <li v-for="(element, index) in Ulname" v-bind:key="index">
            <a href="element.href">
              {{element.text}}              
            </a>
          </li>
        </ul>
    </div>

  </div>
</template>

<script>
export default {
  name: 'HeaderDiTesta',
  data(){
    return{
      Ulname: [
        {
          href: '#',
          text: 'CHARACTERS'
        },
        {
          href: '#',
          text: 'COMICS'
        },
                {
          href: '#',
          text: 'MOVIES'
        },
        {
          href: '#',
          text: 'TV'
        },
        {
          href: '#',
          text: 'GAMES'
        },
        {
          href: '#',
          text: 'COLLECTIBLES'
        },
        {
          href: '#',
          text: 'VIDEOS'
        },
        {
          href: '#',
          text: 'FANS'
        },
        {
          href: '#',
          text: 'NEWS'
        },
        {
          href: '#',
          text: 'SHOP'
        }
      ]

    }

  }
}
</script>


<style scoped lang="scss">

.testa{
  display: flex;
  justify-content: space-between;
  padding-right: 20px;
  padding-right: 20px;
  border: 1px solid red;
  align-items: center;

    .lista ul{
      display: flex;
      flex-wrap: wrap;
      list-style-type: none;
    }
    .lista ul li a{
      text-decoration: none;
      margin: 10px;
      color: black;
      font-family: Arial, Helvetica, sans-serif;
    }
}
</style>