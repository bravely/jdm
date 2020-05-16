<script>
</script>

<header>
  <h1>Jake Demarest-Mays</h1>
  <nav>
    <form>
      <label class="search-label" for="search" aria-labelledby="searchTitle">
        <title id="searchTitle">Search</title>
        🔍
      </label>
    </form>
    <label class="calendar-label" for="date-select" aria-labelledby="dateSelectTitle">
      <title id="dateSelectTitle">Date Select</title>
      🗓
    </label>
    <label class="-label" for="search" aria-labelledby="searchTitle">
      <title id="searchTitle">Search</title>
      🔍
    </label>
  </nav>
</header>

<style>
  header {
    font-family: 'Jost', sans-serif;
    display: flex;
    align-items: center;
    padding: 0 3em;
    background: rgb(0,222,154);
    background: linear-gradient(90deg, rgba(0,222,154,1) 0%, rgba(126,0,255,1) 100%);
    color: #fff;
  }
  nav {
    margin-left: auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }
  label {
    filter: drop-shadow(0 0 0.25rem #333);
  }
</style>
