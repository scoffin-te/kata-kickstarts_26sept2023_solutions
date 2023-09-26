<template>
  <div class="home">
    <main>
      <h1>Welcome to my homepage!</h1>
      <div>
        <img src="../../public/hello-autumn.jpg" alt="">
      </div>
      <article>
        <p>Run a rig belay stern Jack Tar poop deck Davy Jones' Locker fire ship grapple yard long boat. Black jack scourge of the seven seas swing the lead Letter of Marque trysail galleon Pieces of Eight gangway reef bowsprit. Interloper walk the plank reef sails doubloon lad run a shot across the bow broadside Brethren of the Coast line Sail ho.</p>
        <p>Brigantine rutters lad yardarm Barbary Coast Sea Legs Chain Shot mizzen strike colors carouser. Pressgang flogging landlubber or just lubber hulk six pounders Jack Ketch pinnace hands boatswain topsail. Walk the plank yo-ho-ho no prey, no pay brig Sea Legs square-rigged Cat o'nine tails reef grog blossom rutters.</p>
        <p>Reef bounty rum dead men tell no tales clap of thunder pillage driver avast coxswain mizzenmast. Jury mast long boat no prey, no pay yawl Shiver me timbers ahoy gunwalls wherry galleon Pirate Round. Coffer brig blow the man down cable pressgang bilged on her anchor crack Jennys tea cup galleon fire ship coxswain.</p>
        <p>Run a rig belay stern Jack Tar poop deck Davy Jones' Locker fire ship grapple yard long boat. Black jack scourge of the seven seas swing the lead Letter of Marque trysail galleon Pieces of Eight gangway reef bowsprit. Interloper walk the plank reef sails doubloon lad run a shot across the bow broadside Brethren of the Coast line Sail ho.</p>
        <p>Brigantine rutters lad yardarm Barbary Coast Sea Legs Chain Shot mizzen strike colors carouser. Pressgang flogging landlubber or just lubber hulk six pounders Jack Ketch pinnace hands boatswain topsail. Walk the plank yo-ho-ho no prey, no pay brig Sea Legs square-rigged Cat o'nine tails reef grog blossom rutters.</p>
        <p>Reef bounty rum dead men tell no tales clap of thunder pillage driver avast coxswain mizzenmast. Jury mast long boat no prey, no pay yawl Shiver me timbers ahoy gunwalls wherry galleon Pirate Round. Coffer brig blow the man down cable pressgang bilged on her anchor crack Jennys tea cup galleon fire ship coxswain.</p>
        <p>Run a rig belay stern Jack Tar poop deck Davy Jones' Locker fire ship grapple yard long boat. Black jack scourge of the seven seas swing the lead Letter of Marque trysail galleon Pieces of Eight gangway reef bowsprit. Interloper walk the plank reef sails doubloon lad run a shot across the bow broadside Brethren of the Coast line Sail ho.</p>
        <p>Brigantine rutters lad yardarm Barbary Coast Sea Legs Chain Shot mizzen strike colors carouser. Pressgang flogging landlubber or just lubber hulk six pounders Jack Ketch pinnace hands boatswain topsail. Walk the plank yo-ho-ho no prey, no pay brig Sea Legs square-rigged Cat o'nine tails reef grog blossom rutters.</p>
        <p>Reef bounty rum dead men tell no tales clap of thunder pillage driver avast coxswain mizzenmast. Jury mast long boat no prey, no pay yawl Shiver me timbers ahoy gunwalls wherry galleon Pirate Round. Coffer brig blow the man down cable pressgang bilged on her anchor crack Jennys tea cup galleon fire ship coxswain.</p>
      </article>
    </main>
  </div>
</template>

<script>
  export default {
    name: "home",
    data() {
      return {}
    }
  };
</script>

<style scoped>

  div.home {
    height: 100vh;
    overflow: auto;
    padding: 2rem;
  }

  main {
    background-color: var(--ghost);
    padding: 0.5rem;
  }

  main h1 {
    text-align: center;
  }

  main img {
    float: left;
    height: 10rem;
    margin-bottom: 0.25rem;
    margin-right: 0.75rem;
  }

  @media screen and (max-width: 599px) {
    main {
      align-items: center;
      display: flex;
      flex-direction: column;
    }

    main img {
      float: none;
    }
  }
</style>