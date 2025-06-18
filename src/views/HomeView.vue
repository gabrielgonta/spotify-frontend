<script setup>
    import HomeCard from '../components/HomeCard.vue';
</script>

<template>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Your favorite mix
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="/images/albumCovers/clancy.png" style="width: 17%;" title="Clancy" subTitle="Clancy Album" />
            <HomeCard image="/images/albumCovers/top.png" style="width: 17%;" title="Twenty One Pilots" subTitle="Twenty One Pilots songs" />
            <HomeCard class="md:block hidden" image="/images/albumCovers/tyler&josh.png" style="width: 17%;" title="TØP Mix" subTitle="Twenty One Pilots Mix" />
            <HomeCard class="lg:block hidden" image="/images/albumCovers/tvgirl.png" style="width: 17%;" title="Who Really Cares" subTitle="Who Really Cares Album" />
            <HomeCard class="xl:block hidden" image="/images/albumCovers/skillet.png" style="width: 17%;" title="This is Skillet" subTitle="Skillet Mix" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Recommended mix
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="/images/albumCovers/linkinpark.png" style="width: 17%;" title="Rock Mix" subTitle="Avec Linkin Park" />
            <HomeCard image="images/albumCovers/hiphop.png" style="width: 17%;" title="Hip Hop Mix" subTitle="Avec Tyler, The Creator" />
            <HomeCard class="md:block hidden" image="images/albumCovers/indie.png" style="width: 17%;" title="Indie Mix" subTitle="Avec The Neighbourhood" />
            <HomeCard class="lg:block hidden" image="images/albumCovers/billie.png" style="width: 17%;" title="Title is here" subTitle="Mix Billie Eilish" />
            <HomeCard class="xl:block hidden" image="/images/albumCovers/AM.png" style="width: 17%;" title="Arctic Monkeys Mix" subTitle="Mix Arctic Monkeys" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Recommended songs
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="images/albumCovers/trench.png" style="width: 17%;" title="Pet Cheetah" subTitle="2018" />
            <HomeCard image="images/albumCovers/thecontract.png" style="width: 17%;" title="The Contract" subTitle="2025" />
            <HomeCard class="md:block hidden" image="images/albumCovers/Favourite-worst-nightmare.png" style="width: 18.5%;" title="Brianstorm" subTitle="2007" />
            <HomeCard class="lg:block hidden" image="images/albumCovers/frenchexit.png" style="width: 17%;" title="Lovers Rock" subTitle="2014" />
            <HomeCard class="xl:block hidden" image="images/albumCovers/linkin.png" style="width: 17%;" title="Two Faced" subTitle="2024" />
        </div>
    </div>
</template>
