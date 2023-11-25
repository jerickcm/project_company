<script>
import { Head, Link } from "@inertiajs/vue3";
import PublicLayout from "../Layouts/PublicLayout.vue";

export default {
    components: {
        Head,
        PublicLayout,
    },
    setup() {
        return {};
    },
};
</script>

<template>
    <Head title="Homepage" />
    <PublicLayout>
        <nav
            class="top-0 absolute z-50 w-full flex flex-wrap items-center justify-between px-2 py-3"
        >
            <div
                class="container px-4 mx-auto flex flex-wrap items-center justify-between"
            >
                <div
                    class="w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start"
                >
                    <a
                        class="text-sm font-bold leading-relaxed inline-block mr-4 py-2 whitespace-nowrap uppercase text-white"
                        href="https://www.creative-tim.com/learning-lab/tailwind-starter-kit#/presentation"
                        >Mangalus Industries</a
                    ><button
                        class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none"
                        type="button"
                        onclick="toggleNavbar('example-collapse-navbar')"
                    >
                        <i class="text-white fas fa-bars"></i>
                    </button>
                </div>
                <div
                    class="lg:flex flex-grow items-center bg-white lg:bg-transparent lg:shadow-none hidden"
                    id="example-collapse-navbar"
                >
                    <ul class="flex flex-col lg:flex-row list-none mr-auto">
                        <li class="flex items-center">
                            <a
                                class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
                                href="https://www.creative-tim.com/learning-lab/tailwind-starter-kit#/landing"
                                ><i
                                    class="lg:text-gray-300 text-gray-500 far fa-file-alt text-lg leading-lg mr-2"
                                ></i>
                                Contact Us</a
                            >
                        </li>
                        <li class="flex items-center">
                            <a
                                class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
                                href="https://www.creative-tim.com/learning-lab/tailwind-starter-kit#/landing"
                                ><i
                                    class="lg:text-gray-300 text-gray-500 far fa-file-alt text-lg leading-lg mr-2"
                                ></i>
                                About Us</a
                            >
                        </li>
                    </ul>
                    <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
                        <li class="flex items-center">
                            <a
                                class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
                                href="#pablo"
                                ><i
                                    class="lg:text-gray-300 text-gray-500 fab fa-facebook text-lg leading-lg"
                                ></i
                                ><span class="lg:hidden inline-block ml-2"
                                    >Share</span
                                ></a
                            >
                        </li>
                        <li class="flex items-center">
                            <a
                                class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
                                href="#pablo"
                                ><i
                                    class="lg:text-gray-300 text-gray-500 fab fa-twitter text-lg leading-lg"
                                ></i
                                ><span class="lg:hidden inline-block ml-2"
                                    >Tweet</span
                                ></a
                            >
                        </li>
                        <li class="flex items-center">
                            <a
                                class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold"
                                href="#pablo"
                                ><i
                                    class="lg:text-gray-300 text-gray-500 fab fa-github text-lg leading-lg"
                                ></i
                                ><span class="lg:hidden inline-block ml-2"
                                    >Star</span
                                ></a
                            >
                        </li>
                        <li class="flex items-center">
                            <button
                                class="bg-white text-gray-800 active:bg-gray-100 text-xs font-bold uppercase px-4 py-2 rounded shadow hover:shadow-md outline-none focus:outline-none lg:mr-1 lg:mb-0 ml-3 mb-3"
                                type="button"
                                style="transition: all 0.15s ease 0s"
                            >
                                <i class="fas fa-arrow-alt-circle-down"></i>
                                Download
                            </button>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <main>
            <div
                class="relative pt-16 pb-32 flex content-center items-center justify-center"
                style="min-height: 75vh"
            >
                <div
                    class="absolute top-0 w-full h-full bg-center bg-cover"
                    style="background-image: url('/assets/img/homepage.jpg')"
                >
                    <span
                        id="blackOverlay"
                        class="w-full h-full absolute opacity-75 bg-black"
                    ></span>
                </div>
                <div class="container relative mx-auto">
                    <div class="items-center flex flex-wrap">
                        <div
                            class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center"
                        >
                            <div class="pr-12">
                                <h2
                                    class="mb-5 text-blue-300 font-semibold text-3xl"
                                >
                                    Mangalus Industries L.C.
                                </h2>

                                <h1 class="text-white font-semibold text-5xl">
                                    Your story starts with us.
                                </h1>
                                <p class="mt-4 text-lg text-gray-300">
                                    At Mangalus Industries, we excel in crafting
                                    high-performance mining drilling machines
                                    for exploration, blasthole, and production
                                    needs. Count on precision and reliability in
                                    challenging mining environments.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div
                    class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
                    style="height: 70px"
                >
                    <svg
                        class="absolute bottom-0 overflow-hidden"
                        xmlns="http://www.w3.org/2000/svg"
                        preserveAspectRatio="none"
                        version="1.1"
                        viewBox="0 0 2560 100"
                        x="0"
                        y="0"
                    >
                        <!-- class="text-gray-300 fill-current" -->
                        <polygon
                            class="bg-gray-300 fill-current"
                            points="2560 0 2560 100 0 100"
                        ></polygon>
                    </svg>
                </div>
            </div>
            <!-- <section class="pb-20 bg-gray-300 -mt-24"> -->
            <section class="pb-20 bg-gray-300 -mt-24">
                <div class="container mx-auto px-4">
                    <div class="flex flex-wrap">
                        <div
                            class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center"
                        >
                            <div
                                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
                            >
                                <div class="px-4 py-5 flex-auto">
                                    <div
                                        class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-400"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            fill="none"
                                            viewBox="0 0 24 24"
                                            stroke-width="1.5"
                                            stroke="currentColor"
                                            class="w-6 h-6"
                                        >
                                            <path
                                                stroke-linecap="round"
                                                stroke-linejoin="round"
                                                d="M16.5 18.75h-9m9 0a3 3 0 013 3h-15a3 3 0 013-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 01-.982-3.172M9.497 14.25a7.454 7.454 0 00.981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 007.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 002.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 012.916.52 6.003 6.003 0 01-5.395 4.972m0 0a6.726 6.726 0 01-2.749 1.35m0 0a6.772 6.772 0 01-3.044 0"
                                            />
                                        </svg>
                                    </div>
                                    <h6 class="text-xl font-semibold">
                                        Awarded Agency
                                    </h6>
                                    <p class="mt-2 mb-4 text-gray-600">
                                        honored to announce that we have been
                                        awarded for our exceptional
                                        contributions and achievements in the
                                        field, solidifying our commitment to
                                        excellence.
                                    </p>
                                </div>
                            </div>
                        </div>
                        <div class="w-full md:w-4/12 px-4 text-center">
                            <div
                                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
                            >
                                <div class="px-4 py-5 flex-auto">
                                    <div
                                        class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-blue-400"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            fill="none"
                                            viewBox="0 0 24 24"
                                            stroke-width="1.5"
                                            stroke="currentColor"
                                            class="w-6 h-6"
                                        >
                                            <path
                                                stroke-linecap="round"
                                                stroke-linejoin="round"
                                                d="M8.625 9.75a.375.375 0 11-.75 0 .375.375 0 01.75 0zm0 0H8.25m4.125 0a.375.375 0 11-.75 0 .375.375 0 01.75 0zm0 0H12m4.125 0a.375.375 0 11-.75 0 .375.375 0 01.75 0zm0 0h-.375m-13.5 3.01c0 1.6 1.123 2.994 2.707 3.227 1.087.16 2.185.283 3.293.369V21l4.184-4.183a1.14 1.14 0 01.778-.332 48.294 48.294 0 005.83-.498c1.585-.233 2.708-1.626 2.708-3.228V6.741c0-1.602-1.123-2.995-2.707-3.228A48.394 48.394 0 0012 3c-2.392 0-4.744.175-7.043.513C3.373 3.746 2.25 5.14 2.25 6.741v6.018z"
                                            />
                                        </svg>
                                    </div>
                                    <h6 class="text-xl font-semibold">
                                        Support
                                    </h6>
                                    <p class="mt-2 mb-4 text-gray-600">
                                        Our comprehensive maintenance programs
                                        are designed to keep your equipment
                                        operating at its peak. With a responsive
                                        support team available around the clock,
                                        we swiftly address any issues,
                                        minimizing downtime and maximizing
                                        productivity for your operations.
                                    </p>
                                </div>
                            </div>
                        </div>
                        <div class="pt-6 w-full md:w-4/12 px-4 text-center">
                            <div
                                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
                            >
                                <div class="px-4 py-5 flex-auto">
                                    <div
                                        class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-green-400"
                                    >
                                        <svg
                                            xmlns="http://www.w3.org/2000/svg"
                                            fill="none"
                                            viewBox="0 0 24 24"
                                            stroke-width="1.5"
                                            stroke="currentColor"
                                            class="w-6 h-6"
                                        >
                                            <path
                                                stroke-linecap="round"
                                                stroke-linejoin="round"
                                                d="M9 12.75L11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 01-1.043 3.296 3.745 3.745 0 01-3.296 1.043A3.745 3.745 0 0112 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 01-3.296-1.043 3.745 3.745 0 01-1.043-3.296A3.745 3.745 0 013 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 011.043-3.296 3.746 3.746 0 013.296-1.043A3.746 3.746 0 0112 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 013.296 1.043 3.746 3.746 0 011.043 3.296A3.745 3.745 0 0121 12z"
                                            />
                                        </svg>
                                    </div>
                                    <h6 class="text-xl font-semibold">
                                        Verified Company
                                    </h6>
                                    <p class="mt-2 mb-4 text-gray-600">
                                        takes pride in being a verified industry
                                        leader, recognized for our exceptional
                                        contributions and achievements in the
                                        field. This award reaffirms our
                                        commitment to excellence and
                                        credibility.
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-wrap items-center mt-32">
                        <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">
                            <div
                                class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-gray-100"
                            >
                                <svg
                                    xmlns="http://www.w3.org/2000/svg"
                                    viewBox="0 0 20 20"
                                    fill="currentColor"
                                    class="w-8 h-8"
                                >
                                    <path
                                        d="M10 9a3 3 0 100-6 3 3 0 000 6zM6 8a2 2 0 11-4 0 2 2 0 014 0zM1.49 15.326a.78.78 0 01-.358-.442 3 3 0 014.308-3.516 6.484 6.484 0 00-1.905 3.959c-.023.222-.014.442.025.654a4.97 4.97 0 01-2.07-.655zM16.44 15.98a4.97 4.97 0 002.07-.654.78.78 0 00.357-.442 3 3 0 00-4.308-3.517 6.484 6.484 0 011.907 3.96 2.32 2.32 0 01-.026.654zM18 8a2 2 0 11-4 0 2 2 0 014 0zM5.304 16.19a.844.844 0 01-.277-.71 5 5 0 019.947 0 .843.843 0 01-.277.71A6.975 6.975 0 0110 18a6.974 6.974 0 01-4.696-1.81z"
                                    />
                                </svg>
                            </div>
                            <h3
                                class="text-3xl mb-2 font-semibold leading-normal"
                            >
                                Working with us is a pleasure
                            </h3>
                            <p
                                class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-700"
                            >
                                As we seamlessly blend top-tier mining services
                                support with cutting-edge engineering expertise.
                                Our commitment to excellence ensures a rewarding
                                experience, where our comprehensive services not
                                only address your mining needs but also elevate
                                your operations to new heights.
                            </p>
                        </div>
                        <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">
                            <div
                                class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-pink-600"
                            >
                                <img
                                    alt="..."
                                    src="/assets/img/work.jpg"
                                    class="w-full align-middle rounded-t-lg"
                                />
                                <blockquote
                                    class="relative p-8 mb-4 bg-pink-600"
                                >
                                    <svg
                                        preserveAspectRatio="none"
                                        xmlns="http://www.w3.org/2000/svg"
                                        viewBox="0 0 583 95"
                                        class="absolute left-0 w-full block"
                                        style="height: 95px; top: -94px"
                                    >
                                        <polygon
                                            points="-30,95 583,95 583,65"
                                            class="text-pink-600 fill-current"
                                        ></polygon>
                                    </svg>
                                    <h4 class="text-xl font-bold text-white">
                                        Top Notch Services
                                    </h4>
                                    <p
                                        class="text-md font-light mt-2 text-white"
                                    >
                                        We pride ourselves on delivering
                                        top-notch engineering services for
                                        mining drilling machines. Our commitment
                                        to precision, innovation, and unwavering
                                        quality assurance ensures that we stand
                                        at the forefront of the industry,
                                        providing unparalleled solutions that
                                        optimize efficiency and drive success
                                        for our clients."
                                    </p>
                                </blockquote>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section class="relative py-20">
                <div
                    class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
                    style="height: 80px"
                >
                    <svg
                        class="absolute bottom-0 overflow-hidden"
                        xmlns="http://www.w3.org/2000/svg"
                        preserveAspectRatio="none"
                        version="1.1"
                        viewBox="0 0 2560 100"
                        x="0"
                        y="0"
                    >
                        <polygon
                            class="text-white fill-current"
                            points="2560 0 2560 100 0 100"
                        ></polygon>
                    </svg>
                </div>
                <div class="container mx-auto px-4">
                    <div class="items-center flex flex-wrap">
                        <div class="w-full md:w-4/12 ml-auto mr-auto px-4">
                            <img
                                alt="..."
                                class="max-w-full rounded-lg shadow-lg"
                                src="https://images.unsplash.com/photo-1555212697-194d092e3b8f?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=634&amp;q=80"
                            />
                        </div>
                        <div class="w-full md:w-5/12 ml-auto mr-auto px-4">
                            <div class="md:pr-12">
                                <div
                                    class="text-pink-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-pink-300"
                                >
                                    <svg
                                        xmlns="http://www.w3.org/2000/svg"
                                        viewBox="0 0 20 20"
                                        fill="currentColor"
                                        class="w-5 h-5"
                                    >
                                        <path
                                            d="M14.916 2.404a.75.75 0 01-.32 1.012l-.596.31V17a1 1 0 01-1 1h-2.26a.75.75 0 01-.75-.75v-3.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.5a.75.75 0 01-.75.75h-3.5a.75.75 0 010-1.5H2V9.957a.75.75 0 01-.596-1.372L2 8.275V5.75a.75.75 0 011.5 0v1.745l10.404-5.41a.75.75 0 011.012.32zM15.861 8.57a.75.75 0 01.736-.025l1.999 1.04A.75.75 0 0118 10.957V16.5h.25a.75.75 0 110 1.5h-2a.75.75 0 01-.75-.75V9.21a.75.75 0 01.361-.64z"
                                        />
                                    </svg>
                                </div>
                                <h3 class="text-3xl font-semibold">
                                    Our Expertise: Mining Drilling Machines
                                </h3>
                                <p
                                    class="mt-4 text-lg leading-relaxed text-gray-600"
                                >
                                    Precision-engineered, cutting-edge mining
                                    drilling machines. Superior performance in
                                    challenging mining environments. Expertise
                                    in exploration, blasthole, and production
                                    drilling.
                                </p>
                                <ul class="list-none mt-6">
                                    <li class="py-2">
                                        <div class="flex items-center">
                                            <div>
                                                <span
                                                    class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"
                                                    ><svg
                                                        xmlns="http://www.w3.org/2000/svg"
                                                        viewBox="0 0 20 20"
                                                        fill="currentColor"
                                                        class="w-5 h-5"
                                                    >
                                                        <path
                                                            fill-rule="evenodd"
                                                            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z"
                                                            clip-rule="evenodd"
                                                        />
                                                    </svg>
                                                </span>
                                            </div>
                                            <div class="flex flex-row">
                                                <h4 class="text-gray-600">
                                                    Drilling Services
                                                </h4>
                                            </div>
                                        </div>
                                        <div class="pl-10 ml-10">
                                            <ul class="text-gray-600">
                                                <li>
                                                    • Efficient and
                                                    cost-effective solutions by
                                                    a skilled team.
                                                </li>
                                                <li>
                                                    • Prioritizing safety and
                                                    environmental
                                                    responsibility.
                                                </li>
                                            </ul>
                                        </div>
                                    </li>
                                    <li class="py-2">
                                        <div class="flex items-center">
                                            <div>
                                                <span
                                                    class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"
                                                    ><svg
                                                        xmlns="http://www.w3.org/2000/svg"
                                                        viewBox="0 0 20 20"
                                                        fill="currentColor"
                                                        class="w-5 h-5"
                                                    >
                                                        <path
                                                            fill-rule="evenodd"
                                                            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z"
                                                            clip-rule="evenodd"
                                                        />
                                                    </svg>
                                                </span>
                                            </div>
                                            <div>
                                                <h4 class="text-gray-600">
                                                    Installation Services
                                                </h4>
                                            </div>
                                        </div>
                                        <div class="pl-10 ml-10">
                                            <ul class="text-gray-600">
                                                <li>
                                                    • Meticulous assembly and
                                                    integration by an
                                                    experienced team.
                                                </li>
                                                <li>
                                                    • Focus on minimizing
                                                    downtime for optimal
                                                    operational efficiency.
                                                </li>
                                            </ul>
                                        </div>
                                    </li>
                                    <li class="py-2">
                                        <div class="flex items-center">
                                            <div>
                                                <span
                                                    class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"
                                                >
                                                    <svg
                                                        xmlns="http://www.w3.org/2000/svg"
                                                        viewBox="0 0 20 20"
                                                        fill="currentColor"
                                                        class="w-5 h-5"
                                                    >
                                                        <path
                                                            fill-rule="evenodd"
                                                            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z"
                                                            clip-rule="evenodd"
                                                        />
                                                    </svg>
                                                </span>
                                            </div>
                                            <div>
                                                <h4 class="text-gray-600">
                                                    Maintenance and Support
                                                </h4>
                                            </div>
                                        </div>
                                        <div class="pl-10 ml-10">
                                            <ul class="text-gray-600">
                                                <li>
                                                    • Comprehensive maintenance
                                                    programs for peak equipment
                                                    condition.
                                                </li>
                                                <li>
                                                    • Responsive 24/7 support to
                                                    minimize downtime and
                                                    optimize productivity.
                                                </li>
                                            </ul>
                                        </div>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section class="pt-20 pb-48">
                <div class="container mx-auto px-4">
                    <div
                        class="flex flex-wrap justify-center text-center mb-24"
                    >
                        <div class="w-full lg:w-6/12 px-4">
                            <h2 class="text-4xl font-semibold">
                                Here are our heroes
                            </h2>
                        </div>
                    </div>
                    <div class="flex flex-wrap text-center justify-center">
                        <div
                            class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4"
                        >
                            <div class="px-6">
                                <img
                                    alt="..."
                                    src="/assets/img/ceo.jpg"
                                    class="shadow-lg rounded-full max-w-full mx-auto"
                                    style="max-width: 120px"
                                />
                                <div class="pt-6 text-center">
                                    <h5 class="text-xl font-bold">
                                        Engr. Jayson C. Mangalus M.E.
                                    </h5>
                                    <p
                                        class="mt-1 text-sm text-gray-500 uppercase font-semibold"
                                    >
                                        Founder and CEO
                                    </p>
                                    <div class="mt-6">
                                        <a
                                            target="_blank"
                                            href="https://www.linkedin.com/in/jayson-carlos-mangalus-b56b2753/"
                                        >
                                            <button
                                                class="bg-pink-500 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                                                type="button"
                                            >
                                                <img
                                                    src="/assets/img/logo/linkedin-icon-2.svg"
                                                />
                                            </button>
                                        </a>
                                        <a
                                            target="_blank"
                                            href="https://www.facebook.com/jaysoncarlos.mangalus"
                                        >
                                            <button
                                                class="bg-blue-600 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                                                type="button"
                                            >
                                                <img
                                                    src="/assets/img/logo/facebook-3-2.svg"
                                                />
                                            </button>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section class="pb-20 relative block bg-gray-900">
                <div
                    class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
                    style="height: 80px"
                >
                    <svg
                        class="absolute bottom-0 overflow-hidden"
                        xmlns="http://www.w3.org/2000/svg"
                        preserveAspectRatio="none"
                        version="1.1"
                        viewBox="0 0 2560 100"
                        x="0"
                        y="0"
                    >
                        <polygon
                            class="text-gray-900 fill-current"
                            points="2560 0 2560 100 0 100"
                        ></polygon>
                    </svg>
                </div>
                <div class="container mx-auto px-4 lg:pt-24 lg:pb-64">
                    <div class="flex flex-wrap text-center justify-center">
                        <div class="w-full lg:w-6/12 px-4">
                            <h2 class="text-4xl font-semibold text-white">
                                Build something
                            </h2>
                            <p
                                class="text-lg leading-relaxed mt-4 mb-4 text-gray-500"
                            ></p>
                        </div>
                    </div>
                    <div class="flex flex-wrap mt-12 justify-center">
                        <div class="w-full lg:w-3/12 px-4 text-center">
                            <div
                                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
                            >
                                <svg
                                    xmlns="http://www.w3.org/2000/svg"
                                    fill="none"
                                    viewBox="0 0 24 24"
                                    stroke-width="1.5"
                                    stroke="currentColor"
                                    class="w-6 h-6"
                                >
                                    <path
                                        stroke-linecap="round"
                                        stroke-linejoin="round"
                                        d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 00.75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 00-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0112 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 01-.673-.38m0 0A2.18 2.18 0 013 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 013.413-.387m7.5 0V5.25A2.25 2.25 0 0013.5 3h-3a2.25 2.25 0 00-2.25 2.25v.894m7.5 0a48.667 48.667 0 00-7.5 0M12 12.75h.008v.008H12v-.008z"
                                    />
                                </svg>
                            </div>
                            <h6 class="text-xl mt-5 font-semibold text-white">
                                Excellent Services
                            </h6>
                            <p class="mt-2 mb-4 text-gray-500">
                                "With a commitment to unparalleled quality and
                                customer satisfaction, our company distinguishes
                                itself through the delivery of exceptional
                                services that consistently exceed expectations."
                            </p>
                        </div>
                        <div class="w-full lg:w-3/12 px-4 text-center">
                            <div
                                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
                            >
                                <svg
                                    xmlns="http://www.w3.org/2000/svg"
                                    fill="none"
                                    viewBox="0 0 24 24"
                                    stroke-width="1.5"
                                    stroke="currentColor"
                                    class="w-6 h-6"
                                >
                                    <path
                                        stroke-linecap="round"
                                        stroke-linejoin="round"
                                        d="M12 21v-8.25M15.75 21v-8.25M8.25 21v-8.25M3 9l9-6 9 6m-1.5 12V10.332A48.36 48.36 0 0012 9.75c-2.551 0-5.056.2-7.5.582V21M3 21h18M12 6.75h.008v.008H12V6.75z"
                                    />
                                </svg>
                            </div>
                            <h5 class="text-xl mt-5 font-semibold text-white">
                                Grow your market
                            </h5>
                            <p class="mt-2 mb-4 text-gray-500">
                                Fueling market expansion for our partners, we
                                drive growth through innovative solutions and
                                collaborative strategies.
                            </p>
                        </div>
                        <div class="w-full lg:w-3/12 px-4 text-center">
                            <div
                                class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
                            >
                                <svg
                                    xmlns="http://www.w3.org/2000/svg"
                                    fill="none"
                                    viewBox="0 0 24 24"
                                    stroke-width="1.5"
                                    stroke="currentColor"
                                    class="w-6 h-6"
                                >
                                    <path
                                        stroke-linecap="round"
                                        stroke-linejoin="round"
                                        d="M15.59 14.37a6 6 0 01-5.84 7.38v-4.8m5.84-2.58a14.98 14.98 0 006.16-12.12A14.98 14.98 0 009.631 8.41m5.96 5.96a14.926 14.926 0 01-5.841 2.58m-.119-8.54a6 6 0 00-7.381 5.84h4.8m2.581-5.84a14.927 14.927 0 00-2.58 5.84m2.699 2.7c-.103.021-.207.041-.311.06a15.09 15.09 0 01-2.448-2.448 14.9 14.9 0 01.06-.312m-2.24 2.39a4.493 4.493 0 00-1.757 4.306 4.493 4.493 0 004.306-1.758M16.5 9a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0z"
                                    />
                                </svg>
                            </div>
                            <h5 class="text-xl mt-5 font-semibold text-white">
                                Launch time
                            </h5>
                            <p class="mt-2 mb-4 text-gray-500">
                                Minimizing launch times, our company excels
                                through streamlined processes and innovation.
                            </p>
                        </div>
                    </div>
                </div>
            </section>
            <section class="relative block py-24 lg:pt-0 bg-gray-900">
                <div class="container mx-auto px-4">
                    <div class="flex flex-wrap justify-center lg:-mt-64 -mt-48">
                        <div class="w-full lg:w-6/12 px-4">
                            <div
                                class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-300"
                            >
                                <div class="flex-auto p-5 lg:p-10">
                                    <h4 class="text-2xl font-semibold">
                                        Want to work with us?
                                    </h4>
                                    <p
                                        class="leading-relaxed mt-1 mb-4 text-gray-600"
                                    >
                                        Complete this form and we will get back
                                        to you in 24 hours.
                                    </p>
                                    <form
                                        action="mailto:jasonzorro_4@yahoo.com"
                                        method="post"
                                        enctype="text/plain"
                                    >
                                        <div class="relative w-full mb-3 mt-8">
                                            <label
                                                class="block uppercase text-gray-700 text-xs font-bold mb-2"
                                                for="full-name"
                                                >Full Name</label
                                            ><input
                                                type="text"
                                                id="name"
                                                name="name"
                                                class="border-0 px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full"
                                                placeholder="Full Name"
                                                style="
                                                    transition: all 0.15s ease
                                                        0s;
                                                "
                                            />
                                        </div>
                                        <div class="relative w-full mb-3">
                                            <label
                                                class="block uppercase text-gray-700 text-xs font-bold mb-2"
                                                for="email"
                                                >Email</label
                                            ><input
                                                type="email"
                                                id="email"
                                                name="email"
                                                required
                                                class="border-0 px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full"
                                                placeholder="Email"
                                                style="
                                                    transition: all 0.15s ease
                                                        0s;
                                                "
                                            />
                                        </div>
                                        <div class="relative w-full mb-3">
                                            <label
                                                class="block uppercase text-gray-700 text-xs font-bold mb-2"
                                                for="message"
                                                >Message</label
                                            ><textarea
                                                id="message"
                                                name="message"
                                                rows="4"
                                                required
                                                class="border-0 px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full"
                                                placeholder="Type a message..."
                                            ></textarea>
                                        </div>
                                        <div class="text-center mt-6">
                                            <input
                                                class="bg-gray-900 text-white active:bg-gray-700 text-sm font-bold uppercase px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1"
                                                type="submit"
                                                value="Send Message"
                                            />
                                        </div>
                                    </form>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>
    </PublicLayout>
</template>
<style scoped>
:root {
    --tw-ring-color: rgba(59, 130, 246, 0.5);
    --tw-ring-inset: var(--tw-empty);
    --tw-ring-offset-color: #fff;
    --tw-ring-color: rgba(59, 130, 246, 0.5);
    --tw-ring-offset-shadow: 0 0 #0000;
    --tw-ring-shadow: 0 0 #0000;
}
</style>
