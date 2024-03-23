<template>
  <ion-page>
    <ion-tabs>
      <ion-router-outlet></ion-router-outlet>
      <ion-buttons slot="bottom">
        <ion-button
          tab="tab1"
          router-link="/tabs/tab1"
          routerDirection="forward"
        >
          <!-- <ion-icon :icon="timeOutLine" size="large" /> -->
          <ion-label>Tab 1</ion-label>
        </ion-button>
        <ion-button
          tab="tab2"
          router-link="/tabs/tab2"
          routerDirection="forward"
          color="dark"
        >
          <!-- <ion-icon :icon="timeOutLine" size="large" ><ion-icon /> -->
          <ion-label>Tab 2</ion-label>
        </ion-button>
        <ion-button
          tab="tab3"
          router-link="/tabs/tab3"
          routerDirection="forward"
          color="dark"
        >
          <!-- <ion-icon :icon="timeOutLine" size="large" ><ion-icon /> -->
          <ion-label>Tab 2</ion-label>
        </ion-button>
      

        <!-- <ion-tab-button tab="tab2" href="/tabs/tab2">
          <ion-icon aria-hidden="true" :icon="ellipse" />
          <ion-label>Tab 2</ion-label>
        </ion-tab-button>

        <ion-tab-button tab="tab3" href="/tabs/tab3">
          <ion-icon aria-hidden="true" :icon="square" />
          <ion-label>Tab 3</ion-label>
        </ion-tab-button> -->
      </ion-buttons>
    </ion-tabs>
  </ion-page>
</template>

<script lang="ts">
import { ellipse, square, triangle } from 'ionicons/icons';

import {
  IonTabBar,
  IonTabButton,
  IonTabs,
  IonLabel,
  IonIcon,
  IonPage,
  IonRouterOutlet,
  IonButton,
  IonNavLink,
} from '@ionic/vue';

export default {
  components: {
    IonTabBar,
    IonTabButton,
    IonTabs,
    IonLabel,
    IonIcon,
    IonPage,
    IonRouterOutlet,
    IonButton,
    IonNavLink,
  },
};
</script>
