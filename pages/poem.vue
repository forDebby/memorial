<template>
    <div class="container">
        <div class="section links">
            <Nav />
        </div>
        <div class="section details">
            <div class="poem">
                <!-- CONTENT START -->
                <h1 class="title"> Debby Turns Sixty</h1>
                <h4> Hilah Simmons</h4>
                <h4> October 2, 2022</h4>
                <p>
                    T’was an October morn (or was it night?)<br />
                    When you were born<br />
                    In the hospital called New Cornelia,<br />
                    But without your dad there<br />
                    Shirley Talley held Mom’s hand<br />
                    While she screamed and shouted obscenities.<br />
                </p>
                <p>
                    Mayor Gene Talley sent a helicopter<br />
                    To pick up Dad off the mountain,<br />
                    And finally Dad showed up<br />
                    To congratulate the family<br />
                    Who managed to do it without him.<br />
                </p>
                <p>
                    After a few days you and Mom came home,<br />
                    And life hasn’t been the same since.<br />
                    You drank Mom’s milk,<br />
                    But it gave you the colic,<br />
                    And soon you were the one that was screaming.<br />
                </p>
                <p>
                    A papoose board up on Mom’s back<br />
                    Kept you more comfy and happy.<br />
                    We could visit the neighbours<br />
                    Who warned I was risking<br />
                    Your life by putting you out in the sun.<br />
                </p>
                <p>
                    “The coyotes will get her, <br />
                    Mosquitoes will carry her away.”<br />
                    ”I heard her cry; she’s bound to get a hernia<br />
                    Or be burnt to a crisp in the sun.”<br />
                </p>
                <p>
                    Somehow you survived.<br />
                    A few years went by in the Ajo desert<br />
                    With snakes and spiders, a horse and a donkey,<br />
                    And little brother David came along.<br />
                    Before he was one we left Arizona<br />
                    And headed for northern Canada.<br />
                </p>
                <p>

                    In the “garden capital” of the NWt; Fort Smith,<br />
                    When you turned four<br />
                    You were already ready for more<br />
                    Activities, and our next door neighbour<br />
                    Kindergarten teacher<br />
                    Took you in a year early.<br />
                    That way you had two years of kindergarten. <br />
                </p>
                <p>
                    In Fort Smith you won some snowshoe races, <br />
                    Joined the cross country ski team,<br />
                    Played flute in the band,<br />
                    And learned to canoe with the family.<br />
                </p>
                <p>
                    After nine years in Fort Smith<br />
                    With friends like Van Pelts, Kristensons, and Coopers,<br />
                    Building a tree house,<br />
                    And another baby brother Dan,<br />
                    We moved to Yellowknife, capital of the NWT,<br />
                    Where the world opened up for you,<br />
                    And baby sister Sarah joined the family.<br />
                </p>
                <p>
                    Camping with Brownies, Guides, and Beavers,<br />
                    Even meeting the Queen and new friends,<br />
                    You joined choirs, band, orchestra too.<br />
                    You started to travel,<br />
                    To Tuktoyaktuk, to Paris with Dad,<br />
                    And even then to Sahtu<br />
                    Where you had a ride in a real moose skin boat.<br />
                </p>
                <p>
                    You wanted to learn languages<br />
                    And to earn some degrees,<br />
                    Starting off in New Brunswick, then Toronto and York U.,<br />
                    Mexico, and Caraquet.<br />
                    Traveling by plane, bike, foot, and canoe,<br />
                    Gone from the family but home for Christmas.<br />
                    Jobs in the North and Winnipeg too.<br />
                </p>
                <p>
                    You didn’t grow very tall,<br />
                    But you learned through it all<br />
                    How to relate<br />
                    And delegate<br />
                    And let people know what to do.<br />
                </p>
                <p>
                    Once in a while we would go to U.S.,<br />
                    And finally even to Peru and Machu Picchu.<br />
                    As Grandma and Grandpa predicted a world diplomat,<br />
                    But your heart in the North all the while.<br />
                </p>
                <p>
                    You’ve been such a great daughter,<br />
                    Granddaughter, sister, and auntie,<br />
                    Scholar, teacher, example, and friend.<br />
                </p>
                <p>
                    Now you are becoming a champ.<br />
                    You’re a champion not only at Scrabble<br />
                    But a champion of Dene traditions too,<br />
                    And not only that but a champion for wildlife<br />
                    Especially the caribou like your Dad used to do.<br />
                </p>    



                    <!-- CONTENT END -->
            </div>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
div,
h1,
h2,
p {
    margin: 0;
    padding: 0;
    font: 14px Baskerville, Garamond, "Palatino Linotype", "Times New Roman", Times, serif;
    line-height: calc(1ex / 0.32);
    padding: 0.5rem 0rem 0.5rem 1.5rem;
}

.poem {
    background-color: white;
    color: black;
    margin: auto;
    padding: 20px 0;
    text-align: left;
    width: 390px;
}

h1, h2, h4 {
    font-weight: normal;
    color: black;
    text-align: center;
}


.poem h1 {
    font-size: 34px;
    line-height: 1.2;
}

.poem h4 {
    font-size: 18px;    
    font-style: italic;
    margin-bottom: 10px;
    text-align: center;    
}

.poem h2+p:first-letter {
    float: left;
    font-size: 38px;
    line-height: 1;
    margin: 2px 5px 0 0;
}

.poem p:first-line {
    font-variant: small-caps;
    letter-spacing: 1px;
}


.poem p:last-child {
    margin-bottom: 30px;
    padding-bottom: 30px;
}
</style>
