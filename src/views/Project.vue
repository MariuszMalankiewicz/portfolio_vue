<script setup>
    import { Swiper, SwiperSlide } from 'swiper/vue';
    import { EffectCube, Navigation } from "swiper/modules";

    import 'swiper/css/navigation';
    import "swiper/css/effect-cube";
    import 'swiper/css';

</script>

<template>
    <section id="about" class="bg-black min-h-360 w-full min-h-screen flex flex-col justify-center items-center overflow-hidden">
        <h1 class="viewTitle text-white my-24 font-bold text-3xl tracking-wide font-love_ya_like_a_sister"><span class="text-red-500">M</span>oje Projekty</h1>
        <div class="container flex flex-col lg:flex-row justify-center lg:justify-around items-center">
                <Swiper id="video" class="w-full" 
                    :modules="[EffectCube, Navigation]" 
                    effect="cube"
                    navigation>
                    
                    <SwiperSlide>
                        <div class="flex flex-col text-center">
                            <h2 class="title text-white font-semibold font-space_mono mb-5">Perspektywa <span class="text-red-500">superAdmin</span></h2>
                            <video class="mx-auto rounded-xl border-4 border-white" controls>
                                <source :src="`src/assets/videos/MMBlog_super_admin.mp4`" type="video/mp4">
                            </video> 
                        </div>
                    </SwiperSlide>
                    <SwiperSlide>
                        <div class="flex flex-col text-center">
                            <h2 class="title text-white font-semibold font-space_mono mb-5">Perspektywa <span class="text-red-500">Admin</span></h2>
                            <video class="mx-auto rounded-xl border-4 border-white" controls>
                                <source :src="`src/assets/videos/MMBlog_admin.mp4`" type="video/mp4">
                            </video> 
                        </div>
                    </SwiperSlide>
                    <SwiperSlide>
                        <div class="flex flex-col text-center">
                            <h2 class="title text-white font-semibold font-space_mono mb-5">Perspektywa <span class="text-red-500">User</span></h2>
                            <video class="mx-auto rounded-xl border-4 border-white" controls>
                                <source :src="`src/assets/videos/MMBlog_user.mp4`" type="video/mp4">
                            </video> 
                        </div>
                    </SwiperSlide>
                    <SwiperSlide>
                        <div class="flex flex-col text-center">
                            <h2 class="title text-white font-semibold font-space_mono mb-5">Perspektywa <span class="text-red-500">Brak konta</span></h2>
                            <video class="mx-auto rounded-xl border-4 border-white" controls>
                                <source :src="`src/assets/videos/MMBlog_no_account.mp4`" type="video/mp4">
                            </video> 
                        </div>
                    </SwiperSlide>
                </Swiper>

            <div class="description text-center flex flex-col justify-center items-center px-10 lg:px-0 mt-5">
                <h1 class="projectTitle text-white text-md font-agbalumo"><span class="text-red-500">MM</span>Blog</h1>
                <p class="projectTags text-slate-300 font-semibold text-xs my-2 font-space_mono">Laravel 10, PHP 8.1, Mysql 5.7, Tailwind 3.3, Vite 4.0</p>
                <p class="projectContent text-slate-100 text-sm font-space_mono">Oprogramowanie blogowe zależnie od dostępu można tworzyć użytkowników, posty oraz komentarze. Aplikacja korzysta z systemu walidacji do sprawdzania poprawności danych, middleware do ograniczania dostępu oraz relacji pomiędzy użytkownikiem, postami i komentarzami</p>
                <a class="projectButton text-slate-300 hover:text-red-500 ease-in-out duration-300 font-semibold text-md mt-10 lg:mt-5 font-space_mono" href="https://github.com/MariuszMalankiewicz/MMBlog">Zobacz kod</a>

                
            </div>
        </div>
        <div class="line w-4/5 h-0.5 bg-slate-400 m-16 lg:m-24"></div>
    </section>
</template>

<style scoped>
    video{
        max-width: 500px;
        width: 95%;
    }
    .description{
        max-width: 400px;
        width: 100%;
    }
    @media (min-width:1280px) 
    {
        video{
            max-width: 600px;
            width: 100%;
        }
    }

    .viewTitle{
        animation: 
        opacity .5s 1,
        translateX 1s 1 .5s;
    }

    .title{
        animation: 
        opacity 2s 1,
        translateX 1s 1 2s;
    }

    video, #video{
        animation: 
        opacity 1.5s 1,
        translateX 1s 1 1.5s;
    }

    .projectTitle{
        animation: 
        opacity 2s 1,
        translateX 1s 1 2s;
    }
    .projectTags{
        animation: 
        opacity 2.5s 1,
        translateX 1s 1 2.5s;
    }
    .projectContent{
        animation: 
        opacity 3s 1,
        translateX 1s 1 3s;
    }

    .projectButton{
        animation: 
        opacity 3.5s 1,
        translateX 1s 1 3.5s;
    }

    .line{
        animation: 
        opacity 4s 1,
        translateX 1s 1 4s;
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