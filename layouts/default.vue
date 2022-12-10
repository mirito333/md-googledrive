<template>
    <div>
        <Header></Header>
        <div class="flex flex-wrap">
            <div class="
                w-full
                sm:w-3/12
                lg:w-2/12
                pr-4
                tex-left
                absolute
                inset-y-0
                left-0
                transform
                -translate-x-full
                md:relative md:translate-x-0
                transition
                duration-200
                ease-in-out
                bg-slate-200
                z-40
            ">
                <Sidenav />
            </div>
            <div class="w-full sm:w-9/12 lg:w-8/12 px-4 sm:pr-10 lg:pr-4">
                <Nuxt />
            </div>
        </div>
    </div>
</template>