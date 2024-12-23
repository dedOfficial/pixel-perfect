<script>
    import send from '../assets/send.svg';
</script>

<div class="px-5 pt-4 z-10 flex flex-col gap-3">
    <section class="container flex justify-between items-center py-4 px-5 border-solid border" style="border-color: #24FFBC; border-radius: 10px;">
        <div>
            <h3 class="font-semibold text-sm" style="color: #f5f5f5; line-height: 21px;">Send us a message</h3>
            <p class="text-sm font-normal" style="color: #83838d; line-height: 21px;">We typically reply within a day</p>
        </div>
        
        <img src="{send}" alt="send" />
    </section>

    <section class="border border-solid p-2 flex flex-col gap-2" style="background: #0b0b0f; border-radius: 10px; border-color: #15171b;">
        <input placeholder="Search for help" /> 
        <!-- TODO: icon, style placeholded, list -->
        <ul>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
        </ul>
    </section>
</div>