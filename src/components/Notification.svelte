<script>
  let tides = [
    {
      eventID: 1,
      eventName: "Event Name",
      eventDesciption:
        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam corrupti ex iusto maiores deserunt commodi earum dignissimos esse consequatur porro adipisci quasi repudiandae quam, quae laborum architecto veritatis voluptates a?",
    },
    {
      eventID: 2,
      eventName: "Event Name",
      eventDesciption:
        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam corrupti ex iusto maiores deserunt commodi earum dignissimos esse consequatur porro adipisci quasi repudiandae quam, quae laborum architecto veritatis voluptates a?",
    },
    {
      eventID: 3,
      eventName: "Event Name",
      eventDesciption:
        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam corrupti ex iusto maiores deserunt commodi earum dignissimos esse consequatur porro adipisci quasi repudiandae quam, quae laborum architecto veritatis voluptates a?",
    },
    {
      eventID: 4,
      eventName: "Event Name",
      eventDesciption:
        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam corrupti ex iusto maiores deserunt commodi earum dignissimos esse consequatur porro adipisci quasi repudiandae quam, quae laborum architecto veritatis voluptates a?",
    },
  ];
</script>

<div>
  {#each tides as tide}
    <h1>{tide.eventName}</h1>
    <h3>{tide.eventDesciption}</h3>
  {/each}
</div>
