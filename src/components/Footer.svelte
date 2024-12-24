<script>
    import homeActive from '../assets/home_active.svg'
    import messages from '../assets/messages.svg'
    import help from '../assets/help.svg'
    import news from '../assets/news.svg'
</script>

<style>
    .footer-nav {
        line-height: 21px;
        font-weight: 400;
        background: #0B0B0F; 
        box-shadow: 0px 0px 25px 0px rgba(0, 0, 0, 0.05);

        & button {
            padding: 14px 2px;
        }
    }
    .active {
        & span {
            color: #24FFBC;
            font-weight: 600;
        }
    }
</style>

<footer class="text-white text-center font-semibold text-sm p-4 pb-6 pt-0 mt-auto z-10">
    <nav class="footer-nav rounded-lg flex justify-between">
        <button aria-label="Home" class="active w-1/3 border-0 bg-transparent flex flex-col items-center justify-center gap-2">
            <img src="{homeActive}" alt="home">
            <span>Home</span>
        </button>
        <button aria-label="Messages" class="w-1/3 border-0 bg-transparent flex flex-col items-center justify-center gap-2">
            <img src="{messages}" alt="messages">
            <span>Messages</span>
        </button>
        <button aria-label="Help" class="w-1/3 border-0 bg-transparent flex flex-col items-center justify-center gap-2">
            <img src="{help}" alt="help">
            <span>Help</span>
        </button>
        <!-- <button aria-label="News" disabled>
            <img src="{news}" alt="news">
        </button> -->
    </nav>
</footer>