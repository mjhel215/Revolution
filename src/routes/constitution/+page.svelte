<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">REVOLUTION LEAGUE CONSTITUTION</h1>
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>League Rules and Regulations</h2>
    
    <p>All league rules and regulations were voted in by poll format by all initial members of the league. Any further changes shall be voted on by all currently paid and participating league members by poll format in the Sleeper platform in which league majority (with at least ten votes total) will win the poll. In chance of a tie, the league commissioner shall break the tie with a decision leaning towards best practice for all league members. </p>
      
    <h2 class="sectionHeading" bind:this={two}>League Platform</h2>
    
    <p>The current league format is twelve team Dynasty which will be run on the Sleeper platform. Team rosters will be kept by team owners year-round.</p>

    <h2 class="sectionHeading" bind:this={two}>League Fees and Payout</h2>

    <p>The league fee is $50 a year which will be paid in full before we begin our rookie draft. We will use the website Leaguesafe.com as our league bank. Commissioner of the league will release funds to winners as soon as Leaguesafe.com releases the funds upon the fantasy football season ending.</p>
    
    <p>Payouts are as follows: $400 for 1st, $150 for 2nd, $50 for 3rd. Winning payouts are based upon end of season championship playoff bracket outcome. Note: not top points team.</p>
    


</div>
