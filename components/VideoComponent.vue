<template>
    <section class="relative z-0 min-variable-height h-screen w-full bg-red">
        <figure class="left-0 h-screen w-screen absolute bottom-0">
            <div class="absolute top-0 left-0 right-0 h-full w-full opacity-1 pointer-events-none">
                <!-- <button
                    class="absolute top-0 left-0 h-full w-full cursor-default"><span class="sr-only">Play
                        Trailer</span>
                </button> -->
                <video autoplay="true"
                    class="min-w-screen pointer-events-none absolute top-1/2 left-1/2 z-0 min-h-screen -translate-x-1/2 -translate-y-1/2 object-cover">
                    <source src="../assets/videos/teaser.mp4" type="video/mp4">
                    <source src="../assets/videos/teaser.webm" type="video/webm">
                </video>
                <!-- <div
                    class="z-[1] bg-black absolute top-0 left-0 right-0 bottom-0 duration-500 pointer-events-none opacity-1">
                </div>
                <button
                    class="video-button absolute -mt-12 left-6 z-10 text-[30px] text-white duration-500 pointer-events-all opacity-1"><span
                        class="sr-only">Play</span><svg width="15" height="15" viewBox="0 0 15 15" fill="none"
                        xmlns="http://www.w3.org/2000/svg" class="h-[24px] w-[24px]">
                        <path
                            d="M3.24182 2.32181C3.3919 2.23132 3.5784 2.22601 3.73338 2.30781L12.7334 7.05781C12.8974 7.14436 13 7.31457 13 7.5C13 7.68543 12.8974 7.85564 12.7334 7.94219L3.73338 12.6922C3.5784 12.774 3.3919 12.7687 3.24182 12.6782C3.09175 12.5877 3 12.4252 3 12.25V2.75C3 2.57476 3.09175 2.4123 3.24182 2.32181ZM4 3.57925V11.4207L11.4288 7.5L4 3.57925Z"
                            fill="currentColor" fill-rule="evenodd" clip-rule="evenodd"></path>
                    </svg></button><button
                    class="video-button absolute -mt-12 right-6 z-10 text-[30px] text-white duration-500 pointer-events-all opacity-1"><span
                        class="sr-only">Mute</span><svg width="15" height="15" viewBox="0 0 15 15" fill="none"
                        xmlns="http://www.w3.org/2000/svg" class="h-[24px] w-[24px]">
                        <path
                            d="M7.46968 1.05085C7.64122 1.13475 7.75 1.30904 7.75 1.5V13.5C7.75 13.691 7.64122 13.8653 7.46968 13.9492C7.29813 14.0331 7.09377 14.0119 6.94303 13.8947L3.2213 11H1.5C0.671571 11 0 10.3284 0 9.5V5.5C0 4.67158 0.671573 4 1.5 4H3.2213L6.94303 1.10533C7.09377 0.988085 7.29813 0.966945 7.46968 1.05085ZM6.75 2.52232L3.69983 4.89468C3.61206 4.96294 3.50405 5 3.39286 5H1.5C1.22386 5 1 5.22386 1 5.5V9.5C1 9.77615 1.22386 10 1.5 10H3.39286C3.50405 10 3.61206 10.0371 3.69983 10.1053L6.75 12.4777V2.52232ZM10.2784 3.84804C10.4623 3.72567 10.7106 3.77557 10.833 3.95949C12.2558 6.09798 12.2558 8.90199 10.833 11.0405C10.7106 11.2244 10.4623 11.2743 10.2784 11.1519C10.0944 11.0296 10.0445 10.7813 10.1669 10.5973C11.4111 8.72728 11.4111 6.27269 10.1669 4.40264C10.0445 4.21871 10.0944 3.97041 10.2784 3.84804ZM12.6785 1.43044C12.5356 1.2619 12.2832 1.24104 12.1147 1.38386C11.9462 1.52667 11.9253 1.77908 12.0681 1.94762C14.7773 5.14488 14.7773 9.85513 12.0681 13.0524C11.9253 13.2209 11.9462 13.4733 12.1147 13.6161C12.2832 13.759 12.5356 13.7381 12.6785 13.5696C15.6406 10.0739 15.6406 4.92612 12.6785 1.43044Z"
                            fill="currentColor" fill-rule="evenodd" clip-rule="evenodd"></path>
                    </svg></button> -->
            </div>
        </figure>
    </section>
</template>

<!-- playsinline="true" -->