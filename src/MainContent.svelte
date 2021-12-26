<div class="main-content">
  <slot />
</div>

<style>
  .main-content {
    flex: 3;
    padding: var(--default-padding);
    background-color: white;
    display: flex;
    flex-wrap: wrap;
    align-content: flex-start;
  }

  @media (max-width: 456px) {
    .main-content {
      display: flex;
      align-items: center;
      justify-content: center;
    }
  }
</style>
