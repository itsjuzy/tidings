<script>
  let tides = [
    {
      eventID: 1,
      eventName: "Event Name",
      eventDesciption:
        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam corrupti ex iusto maiores deserunt commodi earum dignissimos esse conseqeww",
    },
    {
      eventID: 2,
      eventName: "Event Name",
      eventDesciption:
        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam corrupti ex iusto maiores deserunt commodi earum dignissimos esse conseqeww",
    },
    {
      eventID: 3,
      eventName: "Event Name",
      eventDesciption:
        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam corrupti ex iusto maiores deserunt commodi earum dignissimos esse conseqeww",
    },
    {
      eventID: 4,
      eventName: "Event Name",
      eventDesciption:
        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam corrupti ex iusto maiores deserunt commodi earum dignissimos esse conseqeww",
    },
  ];
</script>

<style>
  .container {
    margin: 1rem;
    padding: 1.5rem;
    background-color: white;
    border-radius: 1em;
    height: 8rem;
  }

  .title {
    padding: 0;
    margin: 0;
    font-size: 1.4rem;
  }

  .desc {
    padding: 0;
    margin: 0;
    font-size: 1rem;
  }
</style>

<div>
  {#each tides as tide}
    <div class="container">
      <h3 class="title">{tide.eventName}</h3>
      <p class="desc">{tide.eventDesciption}</p>
    </div>
  {/each}
</div>
