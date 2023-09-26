<template>
    <div class="about">
        <div class="jumbotron"></div>
        <main>
            <img id="awkseal" src="../../public/awkward-seal.gif" alt="Awkward seal">
            <h1>About Us</h1>
            <p>Prow scuttle parrel provost Sail ho shrouds spirits boom mizzenmast yardarm. Pinnace holystone mizzenmast quarter crow's nest nipperkin grog yardarm hempen halter furl. Swab barque interloper chantey doubloon starboard grog black jack gangway rutters.

    Deadlights jack lad schooner scallywag dance the hempen jig carouser broadside cable strike colors. Bring a spring upon her cable holystone blow the man down spanker Shiver me timbers to go on account lookout wherry doubloon chase. Belay yo-ho-ho keelhaul squiffy black spot yardarm spyglass sheet transom heave to.

    Trysail Sail ho Corsair red ensign hulk smartly boom jib rum gangway. Case shot Shiver me timbers gangplank crack Jennys tea cup ballast Blimey lee snow crow's nest rutters. Fluke jib scourge of the seven seas boatswain schooner gaff booty Jack Tar transom spirits.</p>
        
            <h1>Our Team</h1>
            <div id="team">
              <div class="team-member">
                <img src="../../public/mika.jpg">
                <p>Mika</p>
              </div>
              <div class="team-member">
                <img src="../../public/scuttles.jpg">
                <p>Scuttles</p>
              </div>
              <div>
                <img src="../../public/buoy.jpg">
                <p>Buoy</p>
              </div>
            </div>
        </main>
    </div>
</template>

<style scoped>

  .jumbotron {
    height: 30rem;
    background: url('../../public/lighthouse.jpg');
    background-position: center;
    background-size: cover;
    width: 100%
  }

  div.about {
    height: 100vh;
    overflow: auto;
    padding: 2rem;
  }

  main {
    background-color: var(--ghost);
    padding: 1rem;
  }

  main {
    text-align: center;
  }

  main p {
    text-align: left;
  }

  div#team {
    display: flex;
    justify-content: space-evenly;
  }

  div#team p {
    text-align: center;
  }

  img {
      border: 0.25rem solid var(--black-cat);
      border-radius: 50%;
      height:10rem;
      width: auto;
  }

  #awkseal {
    height: 50%;
    width: auto;
  }

  @media screen and (max-width: 950px) {
    div#team {
      flex-direction: column;
    }
  }
</style>