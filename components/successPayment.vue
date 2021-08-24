<template>
    <div class="">
        <div v-for="detail in details" :key="detail.id" class="">
            <div class="flex py-3 px-1 justify-between">
                <div class="flex">
                    <input class="checkbox mr-3.5" type="checkbox" name="" id="">
                    <h1 class="amount mr-3.5 font-semibold">{{detail.Amount}}</h1>
                    <button class="success mr-4"> <span class="pr-1">{{detail.Status}}</span> <svg width="16"
                            height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M5.97274 11.9097L2.21974 8.19125C1.92724 7.89575 1.92724 7.4165 2.21974 7.12175C2.51224 6.827 2.98774 6.82625 3.28024 7.12175L6.50074 10.2897L12.7167 4.09625C13.0092 3.8015 13.4847 3.8015 13.7772 4.09625C14.0697 4.391 14.0697 4.871 13.7772 5.16575L7.02499 11.906C6.88579 12.0455 6.69705 12.1241 6.50001 12.1248C6.30298 12.1255 6.11368 12.0482 5.97349 11.9097H5.97274Z"
                                fill="#0E6245" />
                        </svg>
                    </button>
                    <p class="ml-3.5 font1">{{detail.Description}}</p>
                </div>
                <div class="flex justify-between">
                    <span class="flex">
                        <p class="pr-6">{{detail.Customer}}</p>
                        <p class="">{{detail.Date}}</p>
                    </span>
                    <p class="pl-10">...</p>
                </div>
            </div>
            <divideLine />
        </div>
    </div>
</template>

<script>
    import divideLine from "../components/divideLine"
    export default {
        components: {
            divideLine
        },
        props: {
            details: {
                type: Array,
                required: true,
                default: () => [{
                    id: 0,
                    Amount: "US$352.22", Status: "Succeded", Description: "fe3d8216-58f9-4dc1-aaef-2f19463b5258",
                    Customer: "hefovo87@ereyemind...", Date: "7 Jul, 14:04"
                }]
            }
        },
    }
</script>
<style>
    .font1 {
        font-family: "SF Pro Display";
    }

    .checkbox {
        /* background: #FFFFFF; */
        border-radius: 4px;
        border: 0.01px solid #ffffff;
        /* box-shadow: 0px 2px 5px rgba(60, 66, 87, 0.08), 0px 0px 0px 1px #3c425729, 0px 1px 1px rgba(0, 0, 0, 0.12); */
        outline: none;
        align-self: center;
    }

    .success {
        display: flex;
        font-size: 12px;
        color: #0E6245;
        background-color: #CBF4C9;
        border-radius: 4px;
        padding: 2px 6px;
        height: 25px;
    }

    .amount {
        width: 86px;
        text-align: right;
    }
</style>