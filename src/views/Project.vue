<template>
    <section id="about" class="bg-black min-h-360 w-full min-h-screen flex flex-col justify-center items-center overflow-hidden">
        <h1 class="text-white my-24 font-bold text-3xl tracking-wide font-love_ya_like_a_sister"><span class="text-red-500">M</span>oje Projekty</h1>

        <div class="container flex flex-col lg:flex-row justify-center lg:justify-around items-center">
            <img class="rounded-full hover:rounded-lg border-4 border-white px-5 hover:px-0 lg:px-10 ease-in-out duration-300" src="../../public/images/przyklad.png" alt="przykladowe_zdj">
            <div class="description text-center flex flex-col justify-center items-center px-10 lg:px-0 mt-5">
                <h1 class="text-white text-md font-agbalumo">Nazwa Projektu</h1>
                <p class="text-slate-300 font-semibold text-xs my-2 font-space_mono">Laravel 10, Vue 3, Tailwind, Npm, Composer</p>
                <p class="text-slate-100 text-sm font-space_mono">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Suscipit, blanditiis repudiandae repellat enim ea placeat minima cum ipsum nobis quo officia, consequatur possimus, dicta neque deserunt. Quam et esse autem enim, beatae dignissimos vel officia quisquam pariatur, ab cumque. Maiores vero eius libero blanditiis! Libero eveniet vitae aspernatur illum obcaecati!</p>
                <a class="text-slate-300 hover:text-red-500 ease-in-out duration-300 font-semibold text-md mt-10 lg:mt-5 font-space_mono" href="#">Zobacz kod</a>
            </div>
        </div>
        <div class="w-4/5 h-0.5 bg-slate-400 m-16 lg:m-24"></div>

        <div class="container flex flex-col lg:flex-row justify-center lg:justify-around items-center">
            <img class="rounded-full hover:rounded-lg border-4 border-white px-5 hover:px-0 lg:px-10 ease-in-out duration-300" src="../../public/images/przyklad.png" alt="przykladowe_zdj">
            <div class="description text-center flex flex-col justify-center items-center px-10 lg:px-0 mt-5">
                <h1 class="text-white text-md font-agbalumo">Nazwa Projektu</h1>
                <p class="text-slate-300 font-semibold text-xs my-2 font-space_mono">Laravel 10, Vue 3, Tailwind, Npm, Composer</p>
                <p class="text-slate-100 text-sm font-space_mono">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Suscipit, blanditiis repudiandae repellat enim ea placeat minima cum ipsum nobis quo officia, consequatur possimus, dicta neque deserunt. Quam et esse autem enim, beatae dignissimos vel officia quisquam pariatur, ab cumque. Maiores vero eius libero blanditiis! Libero eveniet vitae aspernatur illum obcaecati!</p>
                <a class="text-slate-300 hover:text-red-500 ease-in-out duration-300 font-semibold text-md mt-10 lg:mt-5 font-space_mono" href="#">Zobacz kod</a>
            </div>
        </div>
        <div class="w-4/5 h-0.5 bg-slate-400 m-16 lg:m-24"></div>

        
    </section>

    
</template>

<style scoped>
    img{
        max-width: 500px;
        width: 95%;
    }
    .description{
        max-width: 400px;
        width: 100%;
    }
    @media (min-width:1280px) 
    {
        img{
            max-width: 600px;
            width: 100%;
        }
    }

    #about{
        animation: loading 1.5s 1 ease-in-out;
    }

    @keyframes loading {
        0%{
            transform: translateX(-100vw) rotateZ(0deg);
        }
        50%{
            transform: translateX(50vw) rotateZ(10deg) scale(.4);
        }
        75%{
            transform: translateX(-50vw) rotateZ(-10deg) scale(1.4);
        }
        100%{
            transform: translateX(0vw);
        }
    }
    

</style>
<!-- <RouterLink to="/">O Mnie</RouterLink> -->