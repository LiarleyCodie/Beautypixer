<script lang="ts">
import './app.css'

const imageUrl = 'https://images.unsplash.com/photo-1552486289-7a93ac6d69a5?q=80&w=1920'
</script>

<div class='main' style='background-image: url({imageUrl})'>
  <h1 class='h1'>Beautypixer</h1>
  <p>Hi, welcome to the grass land.</p>
</div>

<style lang='scss'>
.main {
  min-height: 100vh;

  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: .4rem;

  background-size: cover;
  background-position: center;

  position: relative;

  color: white;
}

.h1 {
  font-size: 4.8rem;
  line-height: 1;
}
</style>
