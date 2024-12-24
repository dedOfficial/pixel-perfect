<script>
    import send from '../assets/send.svg';
    import search from '../assets/search.svg';
    import arrowLeft from '../assets/arrow_left.svg';
</script>

<style>
    .custom-input {
        background: #1B1E22; 
        padding: 10px 12px;
        line-height: 21px;
        font-size: 14px;

        &::placeholder {
            color: #f5f5f5;
        }
    }

    .list {
        & > li {
            padding: 10px 12px;
            color: #f5f5f5;
            line-height: 21px;
            font-weight: normal;
            font-size: 14px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-radius: 8px;
        }   
    }

    .send-message {
        border-color: #24FFBC; 
        border-radius: 10px; 
        padding: 15.34px 19px; 
        background: #1B1E22; 
        box-shadow: 0px 2px 8px 0px rgba(0, 0, 0, 0.06), 0px 0px 0px 1px rgba(0, 0, 0, 0.08);
    }

    .search {
        background: #0b0b0f; 
        border-radius: 10px;
        box-shadow: 0px 2px 8px 0px rgba(0, 0, 0, 0.06), 0px 0px 0px 1px rgba(0, 0, 0, 0.08);
    }
</style>

<main class="px-4 pt-4 z-10 flex flex-col gap-3">
    <section class="send-message container mx-auto flex justify-between items-center py-4 px-5 border-solid border">
        <div>
            <h3 class="font-semibold text-sm" style="color: #f5f5f5; line-height: 21px;">Send us a message</h3>
            <p class="text-sm font-normal" style="color: #83838d; line-height: 21px;">We typically reply within a day</p>
        </div>
        
        <img src="{send}" alt="send" />
    </section>

    <section class="search p-2 flex flex-col gap-2">
        <div class="relative w-full">
            <input class="custom-input rounded-lg font-semibold w-full" placeholder="Search for help" />
            <img class="absolute top-1/2 right-3 w-4 h-4 -translate-y-1/2" src="{search}" alt="search">
        </div>

        <ul class="list">
            <li>
                <span>In-game bonuses and free spins</span>
                <img src="{arrowLeft}" alt="more" />
            </li>
            <li>
                <span>Crypto deposit still not credited?</span>
                <img src="{arrowLeft}" alt="more" />
            </li>
            <li>
                <span>EigerX VIP program overview</span>
                <img src="{arrowLeft}" alt="more" />
            </li>
            <li>
                <span>Achievements and awards</span>
                <img src="{arrowLeft}" alt="more" />
            </li>
        </ul>
    </section>
</main>