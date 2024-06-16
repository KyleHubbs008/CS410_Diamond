<link rel="stylesheet" type="text/css" href="style.css">


# Team Bios

<style>
.team-bio {
    display: inline-block;
    width: 220px;
    height: 350px;
    margin: 10px;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
    text-align: center;
    box-sizing: border-box;
}
.team-bio img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
}
.team-bio-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}
</style>

## Team Members

<div class="team-bio-container">
    <div class="team-bio">
        <img src="images/kai_image.png" alt="Kai Buckhalter">
        <h3>Kai Buckhalter</h3>
        <p>Short bio for Kai Buckhalter.</p>
    </div>
    <div class="team-bio">
        <img src="images/makendra_image.png" alt="Makendra Crosby">
        <h3>Makendra Crosby</h3>
        <p>Short bio for Makendra Crosby.</p>
    </div>
    <div class="team-bio">
        <img src="images/kyle_image.png" alt="Kyle Hubbs">
        <h3>Kyle Hubbs</h3>
        <p>Short bio for Kyle Hubbs.</p>
    </div>
    <div class="team-bio">
        <img src="images/jordon_image.png" alt="Jordon Kane">
        <h3>Jordon Kane</h3>
        <p>Short bio for Jordon Kane.</p>
    </div>
    <div class="team-bio">
        <img src="images/christian_image.png" alt="Christian Parker">
        <h3>Christian Parker</h3>
        <p>Short bio for Christian Parker.</p>
    </div>
    <div class="team-bio">
        <img src="images/michael_image.png" alt="Michael Porter">
        <h3>Michael Porter</h3>
        <p>Short bio for Michael Porter.</p>
    </div>
    <div class="team-bio">
        <img src="images/emily_image.png" alt="Emily Seepes">
        <h3>Emily Seepes</h3>
        <p>Short bio for Emily Seepes.</p>
    </div>
</div>

<a href="https://KyleHubbs008.github.io/CS410_Diamond/" style="text-decoration: none;">
    <button style="
        display: inline-block;
        padding: 10px 20px;
        font-size: 16px;
        cursor: pointer;
        text-align: center;
        text-decoration: none;
        outline: none;
        color: #000;
        background-color: #FFD700;
        border: none;
        border-radius: 5px;
        transition: background-color 0.3s ease;">
        Back to Homepage
    </button>
</a>

<script>
    document.querySelector('a[href="https://KyleHubbs008.github.io/CS410_Diamond/"] button').addEventListener('mousedown', function() {
        this.style.backgroundColor = '#FFEC8B';
    });
    document.querySelector('a[href="https://KyleHubbs008.github.io/CS410_Diamond/"] button').addEventListener('mouseup', function() {
        this.style.backgroundColor = '#FFD700';
    });
</script>
