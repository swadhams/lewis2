<script>
  import imageqrcode from "./assets/image-qr-code.png";
</script>

<main>
  <div class="body">
    <div class="qrContainer">
        <img class="qrImage" src={imageqrcode} alt="A QR code" />
    <div class="qrWords">
        <h1>Improve your front-end
            skills by building projects
        </h1>
        <p>Scan the QR code to visit Frontend
            Mentor and take your coding skills to
            the next level
        </p>
    </div>
  </div>
</div>
</main>

<style>
    *{
        font-family: "Outfit";
    background:hsl(212, 45%, 89%);
    }
.body{
    width: 100%;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
h1{
    font-size: 21px;
    font-weight: bold;
    background-color: white;
    padding-left: 1rem;;
}


p{
    display: flex;
    font-size: 15px;
    background-color: white;
    color:grey;
    padding-left: 1rem;
}

.qrContainer{
    background-color: white;
    width: 18.5rem;
    display: flex;
    flex-direction: column;
    padding: 1rem;
    border-radius: 1rem;
}
.qrImage {
    max-width: 100%;
    border-radius: 1rem;

}
.qrWords {
background-color: white;
}
</style>
