<template>
    <div class="blackSection1">
        <section class="section1" id="supper-club">
            <h2>Taste Maker</h2>
            <h3>Meet Atlas Supper Club.</h3>
            <p>
                Skip past the endless waitlists and concierge calls that turn up empty handed. With Atlas,
                you have a seat at the table at today's most desirable restaurants.
            </p>
            <img src="../assets/images/horsecard3.JPG" alt="a red horse with wings" />
        </section>
        <section class="writeblock">
            <aside>Dedicated reservations¹</aside>
            <p>
                Access exclusive inventory at our restaurant partners including – Horses, Felix Trattoria,
                Cucina Alba, and more.
            </p>
        </section>
        <section class="writeblock">
            <aside>Last-minute bookings²</aside>
            <p>With bookings available at short notice, you won't find yourself on a waitlist.</p>
        </section>
        <section class="writeblock">
            <aside>Access during peak hours</aside>
            <p>Members get seated at prime time, when availability is typically the hardest to get.</p>
        </section>
        <div class="images3">
            <div class="bottle">
                <picture class="bottle">
                    <source media="(min-width:650px)" srcset="../assets/images/horses.JPG">
                    <source media="(min-width:465px)" srcset="../assets/images/bottle.jpg">
                    <img src="../assets/images/bottle.jpg"
                        alt="a served table with a plate of noodles with a knife and fork, an empty class cup and an opened bottle"/>
                </picture>
                <p>HORSES, LA, ON ATLAS SUPPER CLUB.</p>
            </div>
            <div>
                <img src="../assets/images/felix.jpg" alt="" />
                <p>FELIX TRATTORIA, LA, ON ATLAS SUPPER CLUB.</p>
            </div>
            <div>
                <img src="../assets/images/cucina.jpg" alt="" />
                <p>CUCINA ALBA, NYC, ON ATLAS SUPPER CLUB.</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'SupperClub',
}
</script>