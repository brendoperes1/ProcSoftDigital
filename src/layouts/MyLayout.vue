<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>
        <q-toolbar-title class="absolute-center">
          ProcSoftDigital
        </q-toolbar-title>
         <q-space />
        <div class="row absolute-end">
          <q-btn color="primary" class="btn-size" style="border: 2px solid black" label="Ajuda" @click="showAjuda"/>
          <q-btn color="primary" class="btn-size" style="border: 2px solid black" label="Sobre" @click="showSobre"/>
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <q-dialog v-model="card">
        <q-card class="dialog">
          <q-img src="../statics/diagrama.PNG"/>
        </q-card>
      </q-dialog>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { openURL } from 'quasar'

export default {
  name: 'MyLayout',
  data () {
    return {
      leftDrawerOpen: this.$q.platform.is.desktop,
      card: false
    }
  },
  methods: {
    openURL,
    showAjuda() {
      this.card = true;
    },
    showSobre() {
      this.$q
        .dialog({
          dark: true,
          title:"Sobre",
          message: "O ProcSoft é um jogo educacional baseado na norma ISO/IEC 29110, o jogo foi definido visando apoiar alunos a criarem processos de software que contemplassem as atividades de um ciclo fundamental de desenvolvimento de software e atividades de apoio como gerência de projetos e gerência de configuração. ProcSoft é um jogo de tabuleiro não digital, e seu design final foi baseado no popular jogo comercial Banco Imobiliário. Sendo necessários para execução jogo, o tabuleiro, cartas, dados, peões e peças para marcação de propriedades."
        })
        .onOk(() => {
          console.log("OK");
        })
        .onCancel(() => {
          console.log("Cancel");
        });
    },
  },
  
}
</script>

<style>
.dialog {
  height: 400px;
  width: 500px;
}
</style>
