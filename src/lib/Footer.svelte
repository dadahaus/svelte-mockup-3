<footer>
  <div class="one"><h5>don't hesitate to contact us</h5></div>
  <div class="two row">
    <a href="http://"><div /></a>
    <a href="http://"><div /></a>

    
  </div>
<a class="three" href="http://"><div>or just simply write <img class="mail" src="../../assets/mail-2.svg" alt="mail"></div></a>
</footer>

<style lang="scss">
  footer {
    position: relative;
    display: flex;
    flex-flow: row-reverse;
    align-items: center;
    justify-content: space-between;
    height: calc(90vh);
    width: 100vw;
    padding: 4rem;
    gap: 4rem;

    .one {
      text-transform: uppercase;
      flex-basis: 50%;
      // overflow: hidden;
    }
    .two {
      flex-basis: 50%;
      justify-content: space-evenly;
      gap: 1rem;
      flex-flow: wrap;

      & > * {
        height: 3rem;
        width: 3rem;
        &:nth-child(1) {
          background: center/ cover no-repeat url("../../assets/instagram.svg");
        }
        &:nth-child(2) {
          background: center/ cover no-repeat url("../../assets/dribbble.svg");
        }

      }
    }
    .three{
      position: absolute;
      bottom: 10%;
      right: 10%;
      .mail{
        width: 2rem;
        height: 2rem;
        transform: translateY(30%);
      }
    }
  }
</style>
