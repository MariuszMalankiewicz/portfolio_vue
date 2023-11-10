<template>
    <section id="about" class="bg-black min-h-360 w-full min-h-screen flex flex-col justify-center items-center overflow-hidden">
        <h1 class="viewTitle text-white my-24 font-bold text-3xl tracking-wide font-love_ya_like_a_sister"><span class="text-red-500">M</span>oje Projekty</h1>

        <div class="container flex flex-col lg:flex-row justify-center lg:justify-around items-center">
            <img class="rounded-xl border-4 border-white" src="../../public/images/MMBlog.png" alt="MMBlog">
            <div class="description text-center flex flex-col justify-center items-center px-10 lg:px-0 mt-5">
                <h1 class="projectTitle text-white text-md font-agbalumo"><span class="text-red-500">MM</span>Blog</h1>
                <p class="projectTags text-slate-300 font-semibold text-xs my-2 font-space_mono">Laravel 10, PHP 8.1, Tailwind 3.3, Vite 4.0, Npm, Composer</p>
                <p class="projectContent text-slate-100 text-sm font-space_mono">Aplikacja Blogowa pozwala na zarządzanie <span class="underline decoration-2">postami</span> i <span class="underline decoration-2">komentarzami</span>. Utwórz konto i postuj własne materiały oraz komentuj innych.</p>
                <a class="projectButton text-slate-300 hover:text-red-500 ease-in-out duration-300 font-semibold text-md mt-10 lg:mt-5 font-space_mono" href="#">Zobacz kod</a>
            </div>
        </div>
        <div class="line w-4/5 h-0.5 bg-slate-400 m-16 lg:m-24"></div>



        <div class="container flex flex-col lg:flex-row justify-center lg:justify-around items-center">
            <img class="rounded-xl border-4 border-white" src="../../public/images/przyklad.png" alt="przykladowe_zdj">
            <div class="description text-center flex flex-col justify-center items-center px-10 lg:px-0 mt-5">
                <h1 class="projectTitle text-white text-md font-agbalumo"><span class="text-red-500">MM</span>Blog</h1>
                <p class="projectTags text-slate-300 font-semibold text-xs my-2 font-space_mono">Laravel 10, PHP 8.1, Tailwind 3.3, Vite 4.0, Npm, Composer</p>
                <p class="projectContent text-slate-100 text-sm font-space_mono">Aplikacja Blogowa pozwala na zarządzanie postami i komentarzami. Utwórz konto i postuj własne materiały oraz komentuj innych.</p>
                <a class="projectButton text-slate-300 hover:text-red-500 ease-in-out duration-300 font-semibold text-md mt-10 lg:mt-5 font-space_mono" href="#">Zobacz kod</a>
            </div>
        </div>
        <div class="line w-4/5 h-0.5 bg-slate-400 m-16 lg:m-24"></div>

        
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

    /* #about{
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
    } */

    .viewTitle{
        animation: 
        opacity .5s 1,
        translateX 1s 1 .5s;
    }

    img{
        animation: 
        opacity 1s 1,
        translateX 1s 1 1s;
    }

    .projectTitle{
        animation: 
        opacity 1.5s 1,
        translateX 1s 1 1.5s;
    }
    .projectTags{
        animation: 
        opacity 2s 1,
        translateX 1s 1 2s;
    }
    .projectContent{
        animation: 
        opacity 2.5s 1,
        translateX 1s 1 2.5s;
    }

    .projectButton{
        animation: 
        opacity 3s 1,
        translateX 1s 1 3s;
    }

    .line{
        animation: 
        opacity 3.5s 1,
        translateX 1s 1 3.5s;
    }

    @keyframes opacity {
        0%{
            opacity: 0;
        }
        99%{
            opacity: 0;
        }
        100%{
            opacity: 1;
            transform: translateX(-15%);
        }
    }

    @keyframes translateX {
        0%{
            transform: translateX(-15%);
        }
        100%{
            transform: translateX(0);
        }
    }
    

</style>
<!-- <RouterLink to="/">O Mnie</RouterLink> -->