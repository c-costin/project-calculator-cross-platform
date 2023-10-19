
<section class="keyboard">
    <div class="keyboard__nums">
        <button class="keyboard__btn">7</button>
        <button class="keyboard__btn">8</button>
        <button class="keyboard__btn">9</button>
        <button class="keyboard__btn">4</button>
        <button class="keyboard__btn">5</button>
        <button class="keyboard__btn">6</button>
        <button class="keyboard__btn">1</button>
        <button class="keyboard__btn">2</button>
        <button class="keyboard__btn">3</button>
        <button class="keyboard__btn">0</button>
    </div>
    <div class="keyboard__actions">
        <button class="keyboard__btn">÷</button>
        <button class="keyboard__btn">×</button>
        <button class="keyboard__btn">-</button>
        <button class="keyboard__btn">+</button>
        <button class="keyboard__btn">=</button>
    </div>
</section>

<style lang="scss">
    .keyboard {
        width: 100%;
        height: 70%;
        display: flex;
        gap: 1rem;
        &__nums {
            width: 75%;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1rem;
        }
        &__actions {
            width: 25%;
            display: grid;
            grid-template-columns: repeat(1, 1fr);
            gap: 1rem;
        }
        &__btn {
            width: 100%;
            height: 100%;
            border: none;
            border-radius: 0.5rem;
            background: none;
            box-shadow: rgba(60, 64, 67, 0.3) 0px 1px 2px 0px, rgba(60, 64, 67, 0.15) 0px 1px 3px 1px;
        }
    }
</style>