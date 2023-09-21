<template>
  <div class="app-header">
    <div class="app-header-name">
      <img src="../app-icon.svg" alt="Better Shadows">
      <span>Better Shadows</span>
    </div>

    <div class="close">
      <svg
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 16 16"
      >
        <path d="M3.414 2 2 3.414 6.586 8 2 12.586 3.414 14 8 9.414 12.585 14 14 12.585 9.414 8 14 3.415 12.585 2 8 6.586 3.414 2Z" fill="currentColor"/>
      </svg>
    </div>
  </div>
</template>

<style lang="scss">
.app-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 40px;
  width: 100%;
  padding: 8px;
  background-color: var(--background1);
  font-weight: 700;
  color: var(--text1);

  .app-header-name {
    display: flex;
    align-items: center;

    img {
      width: 24px;
      height: 24px;
      margin-right: 8px;
    }

  }
  .close{ 
    display: flex;
    align-items: center;
    justify-content: center;
    width: 24px;
    height: 24px;
    border-radius: 2px;
    background-color: transparent;

    svg{
      display: block;
      width: 16px;
      height: 16px;
    }

    &:hover {
      background-color: var(--background2);
      color: var(--text1);
    }
  }
}
</style>