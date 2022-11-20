<main>
  <header>
    <div class="summary">
      <span>My Balance</span>
      <span>$921.48</span>
    </div>
    <div class="icon">
      <svg
        width="72"
        height="48"
        viewBox="0 0 72 48"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <circle cx="48" cy="24" r="24" fill="#382314" />
        <circle cx="24" cy="24" r="23" stroke="white" stroke-width="2" />
      </svg>
    </div>
  </header>
</main>

<style>
    main {
        min-width: 540px;
    }
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;

        padding: 28px 32px;

        background-color: var(--red);
        border-radius: 20px;
        width: 100%;
        color: var(--white);
    }

    .summary {
        display: flex;
        flex-direction: column;
    }
    .summary span:first-child {
        font-size: 1rem;
        font-weight: 300;
        margin-bottom: 12px;
    }

    .summary span:last-child {
        font-size: 2rem;
        font-weight: 900;
    }

    .icon {
        display: flex;
    }
</style>