<template>
  <nb-container :style="{backgroundColor: '#fff'}">
        <nb-header>
          <nb-left>
            <nb-button
              transparent
              :onPress="() => this.props.navigation.goBack()"
            >
              <nb-icon name="arrow-back" />
            </nb-button>
          </nb-left>
          <nb-body>
            <nb-title>Regular</nb-title>
          </nb-body>
          <nb-right />
        </nb-header>

       <nb-content padder>
            <nb-form>
                <nb-item regular>
                    <nb-input placeholder="Regular Textbox" />
                </nb-item>
            </nb-form>
       </nb-content>
      </nb-container>
</template>