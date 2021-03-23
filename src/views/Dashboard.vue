<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-menu-button color="primary"></ion-menu-button>
        </ion-buttons>
        <ion-title>Dasbhoard</ion-title>
      </ion-toolbar>
    </ion-header>
    
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Dasbhoard</ion-title>
        </ion-toolbar>
      </ion-header>
      
      <ion-title size="large" class="ion-margin-top">Partite in corso</ion-title>

      <ion-list>
        <ion-item>
          <ion-label>Milan - Juventus</ion-label>
          <ion-avatar slot="start">
            <img src="https://upload.wikimedia.org/wikipedia/it/f/f5/Logo_Serie_A_TIM_2019.png">
          </ion-avatar>
        </ion-item>
        <ion-item>
          <ion-label>Milan - Juventus</ion-label>
          <ion-avatar slot="start">
            <img src="https://upload.wikimedia.org/wikipedia/it/f/f5/Logo_Serie_A_TIM_2019.png">
          </ion-avatar>
        </ion-item>
        <ion-item>
          <ion-label>Milan - Juventus</ion-label>
          <ion-avatar slot="start">
            <img src="https://upload.wikimedia.org/wikipedia/it/f/f5/Logo_Serie_A_TIM_2019.png">
          </ion-avatar>
        </ion-item>
        <ion-item>
          <ion-label>Milan - Juventus</ion-label>
          <ion-avatar slot="start">
            <img src="https://upload.wikimedia.org/wikipedia/it/f/f5/Logo_Serie_A_TIM_2019.png">
          </ion-avatar>
        </ion-item>
      </ion-list>

      <ion-title size="large" class="ion-margin-top">Partite in scadenza</ion-title>

      <ion-list>
        <ion-item>
          <ion-label>Milan - Juventus</ion-label>
          <ion-avatar slot="start">
            <img src="https://upload.wikimedia.org/wikipedia/it/f/f5/Logo_Serie_A_TIM_2019.png">
          </ion-avatar>
        </ion-item>
        <ion-item>
          <ion-label>
            <h4>Milan - Juventus</h4>
            <h6>12/12/12</h6>
            <p>Giornata 7</p>
          </ion-label>
          <ion-thumbnail slot="start">
            <ion-img src="https://upload.wikimedia.org/wikipedia/it/f/f5/Logo_Serie_A_TIM_2019.png"></ion-img>
          </ion-thumbnail>
        </ion-item>
        <ion-item>
          <ion-label>Milan - Juventus</ion-label>
          <ion-thumbnail slot="start">
            <img src="https://upload.wikimedia.org/wikipedia/it/f/f5/Logo_Serie_A_TIM_2019.png">
          </ion-thumbnail>
        </ion-item>
        <ion-item>
          <ion-label>Milan - Juventus</ion-label>
          <ion-avatar slot="start">
            <img src="https://upload.wikimedia.org/wikipedia/it/f/f5/Logo_Serie_A_TIM_2019.png">
          </ion-avatar>
        </ion-item>
      </ion-list>


    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonButtons, IonContent, IonHeader, IonMenuButton, IonPage, IonTitle, IonToolbar } from '@ionic/vue';

export default {
  name: 'Folder',
  components: {
    IonButtons,
    IonContent,
    IonHeader,
    IonMenuButton,
    IonPage,
    IonTitle,
    IonToolbar
  }
}
</script>

<style scoped>
#container {
  text-align: center;
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  color: #8c8c8c;
  margin: 0;
}

#container a {
  text-decoration: none;
}
</style>