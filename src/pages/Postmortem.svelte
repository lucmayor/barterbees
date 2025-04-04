<script>
    import Page from "../lib/Page.svelte";
</script>

<Page>
    <p><b>What went right in the development process?</b></p>

    <p>We believe that the best aspect of our development is our first strikeback after Iteration One. As a team, we realized immediately the biggest aspects of what wasn't working -- there was a major lack of communication and a severe need to move time estimates up. We decided to plan for an earlier time to finish the iteration and for more frequent meetings. As a whole, everyone was significantly more vocal and communicative during the second iteration. Unfortunately, it must be said that we needed to cover more in terms of improvement to fully encompass what was needed to save our project -- and after an emergency meeting during the third iteration, we responded to external criticisms fast and efficiently, and produced a final product that we are happy with.</p>

    <p><b>What would you do differently, if you had the chance to start over?</b></p>

    <p>If we were to approach this project again, the most prominent change we would make would be creating a stronger schedule earlier within the project. We had a strong concept, and teammates willing and capable of performing what was asked of such daring feats, but fell short in overall planning for production and scheduling of production within our first iteration, which caused us to start off on a wrong foot that we never fully recovered from. Similarly, if we were to start from the middle of the project post-Iteration One, we would probably benefit from better focused communication and decision making, reeling back our ambition to better focus on the present work quality. This was something we did end up discussing within both our Iteration Two retrospective and within an additional team-educator meeting shortly after Iteration Three began. </p>

    <p><b>What took the most time? The least? Any surprises?</b></p>

    <p>Overall, what probably took the most time was either In-App Chat (if we are counting parts that did not make it to the final iteration) or Swipe. Swipe started as a generally simple concept to build, but was constantly slowed by unexpected roadblocks. This started in Iteration One, where we had no good idea of how to properly pass the database. This was extended to Iteration Two, where we finally began implementing the database properly with our SQL based HSQLDB. Finally, in Iteration Three, we noticed a discrepancy in test behavior from any implementation using the stub DB. Fixing this unintended behavior required the addition of multiple relational tables within our SQL database. As for the least amount of time, we could probably point to the implementation of the stub database, which was one of the few implemented aspects of the codebase that followed the expected implementation schedule. There was no major surprises, save for the general initial shock from the first iteration.</p>
</Page>

<style>
    p {
        margin: 3px
    }
</style>