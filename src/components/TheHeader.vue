<template>
    <nav class=" bg-menu w-full flex relative justify-between items-center mx-auto px-8 h-20 bg-100">
        <!-- logo -->
        <div class="inline-flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
                class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round"
                    d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5" />
            </svg>



            <h1 class="text-2xl font-bold px-2 text-orange-500">Scoolez</h1>
        </div>

        <!-- end logo -->

        <!-- second menu  bar -->
        <div class="hidden sm:block flex-shrink flex-grow-0 justify-start px-2">
            <div class="inline-block">
                <div class="inline-flex items-center max-w-full ">

                    <a class="inline-block py-2 px-10  " href="#">
                        <div class="flex items-center relative cursor-pointer whitespace-nowrap">Academics</div>
                    </a>
                    <a class="inline-block py-2 px-10  " href="#">
                        <div class="flex items-center relative cursor-pointer whitespace-nowrap">Enroll</div>
                    </a>
                    <a class="inline-block py-2 px-10  " href="#">
                        <div class="flex items-center relative cursor-pointer whitespace-nowrap">Curriculum</div>
                    </a>
                    <a class="inline-block py-2 px-10  " href="#">
                        <div class="flex items-center relative cursor-pointer whitespace-nowrap">Testimonials</div>
                    </a>
                    <button class=" border-0 py-2 px-6 mx-4 focus:outline-none rounded text-md">Contact us</button>

                </div>
            </div>
        </div>
        <!-- end of second menu bar -->

        <!-- login -->
        <div class="flex-initial">
            <div class="flex justify-end items-center relative">
                <div class="flex mr-4 items-center">
                    <a class="inline-block py-2 px-10 bg-btn" href="#">
                        <div class="flex items-center relative cursor-pointer whitespace-nowrap bg-transparent">Create an Account</div>
                    </a>

                </div>
            </div>
        </div>
    </nav>
</template>

<style>
.bg-menu {
    /* background-color: rgb(191, 191, 191); */
    /* color: ; */
    color: #1E1822
}

.bg-btn {
    /* background-color: #1E1822; */
    color: black;
    border: 1px solid rgb(249 115 22 );
}
</style>
