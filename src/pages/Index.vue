<template>
  <div class="row q-pa-md" style="full">
    <div class="row q-pa-md">
      <div class="column items-start">
        <div class="row">
          <q-btn class="btn-size" style="border: 2px solid black" label="Papel" color="grey" />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="2"
            color="purple"
            @click="showAtiv(2)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="3"
            color="green"
            @click="showAtiv(3)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="4"
            color="purple"
            @click="showAtiv(4)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="5"
            color="red"
            @click="showAtiv(5)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="6"
            color="green"
            @click="showAtiv(6)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="7"
            color="orange"
            @click="showAtiv(7)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="8"
            color="purple"
            @click="showAtiv(8)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="9"
            color="orange"
            @click="showAtiv(9)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="10"
            color="red"
            @click="showAtiv(10)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="11"
            color="purple"
            @click="showAtiv(11)"
          />
        </div>
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="44"
          color="orange"
          @click="showAtiv(44)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="43"
          color="red"
          @click="showAtiv(43)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="42"
          color="purple"
          @click="showAtiv(42)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="41"
          color="orange"
          @click="showAtiv(41)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="40"
          color="red"
          @click="showAtiv(40)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="39"
          color="purple"
          @click="showAtiv(39)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="38"
          color="green"
          @click="showAtiv(38)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="37"
          color="red"
          @click="showAtiv(37)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="36"
          color="purple"
          @click="showAtiv(36)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="35"
          color="red"
          @click="showAtiv(35)"
        />

        <div class="row">
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="S/R"
            color="grey"
            @click="showSortReves()"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="33"
            color="red"
            @click="showAtiv(33)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="32"
            color="orange"
            @click="showAtiv(32)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="31"
            color="purple"
            @click="showAtiv(31)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="30"
            color="red"
            @click="showAtiv(30)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="29"
            color="green"
            @click="showAtiv(29)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="28"
            color="red"
            @click="showAtiv(28)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="27"
            color="orange"
            @click="showAtiv(27)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="26"
            color="green"
            @click="showAtiv(26)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="25"
            color="green"
            @click="showAtiv(25)"
          />
          <q-btn
            class="btn-size"
            style="border: 2px solid black"
            label="24"
            color="orange"
            @click="showAtiv(24)"
          />
        </div>
      </div>
      <div class="column items-start">
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="Dinheiro"
          @click="addDinheiro()"
          color="grey"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="13"
          color="red"
          @click="showAtiv(13)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="14"
          color="purple"
          @click="showAtiv(14)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="15"
          color="orange"
          @click="showAtiv(15)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="16"
          color="green"
          @click="showAtiv(16)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="17"
          color="orange"
          @click="showAtiv(17)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="18"
          color="purple"
          @click="showAtiv(18)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="19"
          color="green"
          @click="showAtiv(19)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="20"
          color="green"
          @click="showAtiv(20)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="21"
          color="red"
          @click="showAtiv(21)"
        />
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="22"
          color="purple"
          @click="showAtiv(22)"
        />

        <q-btn class="btn-size" style="border: 2px solid black" label="Ferram." color="grey" />
      </div>
    </div>

    <div class="column" style="margin-top: 15px;">
      <div class="row">
        <q-btn
          class="btn-size"
          style="border: 2px solid black"
          label="Dado"
          color="primary"
          @click="dado()"
        />
        <q-input class="inputDado" v-model="dadoVal" label="Último valor do dado" />
        <q-btn
          class="btn-pergunta"
          style="border: 2px solid black"
          label="Perguntas"
          color="primary"
          @click="showPergunta()"
        />
        <q-btn
          class="btn-pergunta"
          style="border: 2px solid black"
          label="+ TIME"
          color="primary"
          @click="prompt = true"
        />
      </div>

      <q-dialog v-model="promptGerenciarDinheiro" persistent>
        <q-card style="min-width: 350px">
          <q-card-section>
            <div class="text-h6">Dinheiro</div>
          </q-card-section>

          <q-card-section>
            <q-input dense v-model="adicionarDinheiro" autofocus />
          </q-card-section>

          <q-card-actions align="right" class="text-primary">
            <q-btn flat label="Cancel" v-close-popup />
            <q-btn
              flat
              label="Gerenciar $$"
              @click="gerenciarDinheiro(adicionarDinheiro)"
              v-close-popup
            />
          </q-card-actions>
        </q-card>
      </q-dialog>

      <q-dialog v-model="promptAddAtividade" persistent>
        <q-card style="min-width: 350px">
          <q-card-section>
            <div class="text-h6">Atividade</div>
          </q-card-section>

          <q-card-section>
            <q-input dense v-model="adicionarAtividade" autofocus />
          </q-card-section>

          <q-card-actions align="right" class="text-primary">
            <q-btn flat label="Cancel" v-close-popup />
            <q-btn
              flat
              label="Add Atividade"
              @click="verAtividades(adicionarAtividade)"
              v-close-popup
            />
          </q-card-actions>
        </q-card>
      </q-dialog>

      <q-dialog v-model="prompt" persistent>
        <q-card style="min-width: 350px">
          <q-card-section>
            <div class="text">Nome do time</div>
          </q-card-section>
          <q-card-section>
            <q-input dense v-model="nomeTIME" autofocus />
          </q-card-section>
          <q-card-section>
            <div class="text">Nome dos participantes</div>
          </q-card-section>
          <q-card-section>
            <q-input dense v-model="nomesPARTICIPANTES" autofocus />
          </q-card-section>

          <q-card-actions align="right" class="text-primary">
            <q-btn flat label="Cancel" v-close-popup />
            <q-btn
              flat
              label="Adicionar Time"
              @click="addTime(nomeTIME, nomesPARTICIPANTES)"
              v-close-popup
            />
          </q-card-actions>
        </q-card>
      </q-dialog>

      <q-dialog v-model="mostrarPapeis1">
        <q-card style="width: 300px" class="q-px-sm q-pb-md">
          <q-card-section>
            <q-option-group v-model="group1" :options="options1" color="green" type="checkbox" />
          </q-card-section>
        </q-card>
      </q-dialog>
      <q-dialog v-model="mostrarPapeis2">
        <q-card style="width: 300px" class="q-px-sm q-pb-md">
          <q-card-section>
            <q-option-group v-model="group2" :options="options2" color="green" type="checkbox" />
          </q-card-section>
        </q-card>
      </q-dialog>
      <q-dialog v-model="mostrarPapeis3">
        <q-card style="width: 300px" class="q-px-sm q-pb-md">
          <q-card-section>
            <q-option-group v-model="group3" :options="options3" color="green" type="checkbox" />
          </q-card-section>
        </q-card>
      </q-dialog>

      <q-dialog v-model="mostrarFerramentas1">
        <q-card style="width: 300px" class="q-px-sm q-pb-md">
          <q-card-section>
            <q-option-group v-model="grupo1" :options="options4" color="green" type="checkbox" />
          </q-card-section>
        </q-card>
      </q-dialog>
      <q-dialog v-model="mostrarFerramentas2">
        <q-card style="width: 300px" class="q-px-sm q-pb-md">
          <q-card-section>
            <q-option-group v-model="grupo2" :options="options5" color="green" type="checkbox" />
          </q-card-section>
        </q-card>
      </q-dialog>
      <q-dialog v-model="mostrarFerramentas3">
        <q-card style="width: 300px" class="q-px-sm q-pb-md">
          <q-card-section>
            <q-option-group v-model="grupo3" :options="options6" color="green" type="checkbox" />
          </q-card-section>
        </q-card>
      </q-dialog>

      <div class="column">
        <q-card v-if="time1aux" dark bordered class="bg-grey-9 my-card">
          <q-card-section>
            <div class="text-h6">
              Time {{time1.nomeTime1}} Casa: {{time1.casaTime1}} Dinheiro: {{time1.dinheiro1}}
              <q-radio v-model="shape" val="time1" />
            </div>
            <div class="text-subtitle2">{{time1.partTime1}}</div>
          </q-card-section>

          <q-separator dark inset />

          <q-card-section>
            <q-btn flat label="Papeis" @click="showPapeis()" v-close-popup />

            <q-btn flat label="Ferramentas" @click="showFerramentas()" v-close-popup />
            <br />
            <q-btn flat label="Add Atividades" @click="addAtividades()" v-close-popup />

            <q-btn flat label="Gerenciar $$" @click="dinheiroTime()" v-close-popup />
          </q-card-section>
          <q-card-section>
            <div class="text-h6">Atividades: {{time1.atividades1}}</div>
          </q-card-section>
        </q-card>
        <q-card v-if="time2aux" dark bordered class="bg-grey-9 my-card">
          <q-card-section>
            <div class="text-h6">
              Time {{time2.nomeTime2}} Casa: {{time2.casaTime2}} Dinheiro: {{time2.dinheiro2}}
              <q-radio v-model="shape" val="time2" />
            </div>
            <div class="text-subtitle2">{{time2.partTime2}}</div>
          </q-card-section>

          <q-separator dark inset />

          <q-card-section>
            <q-btn flat label="Papeis" @click="showPapeis2()" v-close-popup />

            <q-btn flat label="Ferramentas" @click="showFerramentas2()" v-close-popup />
            <br />
            <q-btn flat label="Add Atividades" @click="addAtividades()" v-close-popup />

            <q-btn flat label="Gerenciar $$" @click="dinheiroTime()" v-close-popup />
          </q-card-section>
          <q-card-section>
            <div class="text-h6">Atividades: {{time2.atividades2}}</div>
          </q-card-section>
        </q-card>
        <q-card v-if="time3aux" dark bordered class="bg-grey-9 my-card">
          <q-card-section>
            <div class="text-h6">
              Time {{time3.nomeTime3}} Casa: {{time3.casaTime3}} Dinheiro: {{time3.dinheiro3}}
              <q-radio v-model="shape" val="time3" />
            </div>
            <div class="text-subtitle2">{{time3.partTime3}}</div>
          </q-card-section>

          <q-separator dark inset />

          <q-card-section>
            <q-btn flat label="Papeis" @click="showPapeis3()" v-close-popup />

            <q-btn flat label="Ferramentas" @click="showFerramentas3()" v-close-popup />
            <br />
            <q-btn flat label="Add Atividades" @click="addAtividades()" v-close-popup />

            <q-btn flat label="Gerenciar $$" @click="dinheiroTime()" v-close-popup />
          </q-card-section>
          <q-card-section>
            <div class="text-h6">Atividades: {{time3.atividades3}}</div>
          </q-card-section>
        </q-card>
      </div>
    </div>
  </div>
</template>

<script>
import {
  sorte_reves,
  atividades,
  perguntas,
  papeis,
  papeis2,
  papeis3,
  ferramentas,
  ferramentas2,
  ferramentas3
} from "../enums";

export default {
  name: "PageIndex",
  data() {
    return {
      group1: [""],
      options1: papeis,
      group2: [""],
      options2: papeis2,
      group3: [""],
      options3: papeis3,
      grupo1: [""],
      options4: ferramentas,
      grupo2: [""],
      options5: ferramentas2,
      grupo3: [""],
      options6: ferramentas3,
      dadoVal: null,
      prompt: false,
      promptAddAtividade: false,
      promptGerenciarDinheiro: false,
      adicionarDinheiro: null,
      nomeTIME: "",
      nomesPARTICIPANTES: "",
      shape: "",
      adicionarAtividade: "",
      mostrarPapeis1: false,
      mostrarPapeis2: false,
      mostrarPapeis3: false,
      mostrarFerramentas1: false,
      mostrarFerramentas2: false,
      mostrarFerramentas3: false,
      model: null,
      time1: {
        nomeTime1: "",
        partTime1: "",
        casaTime1: 0,
        dinheiro1: 2100,
        atividades1: []
      },
      time2: {
        nomeTime2: "",
        partTime2: "",
        casaTime2: 0,
        dinheiro2: 2100,
        atividades2: []
      },
      time3: {
        nomeTime3: "",
        partTime3: "",
        casaTime3: 0,
        dinheiro3: 2100,
        atividades3: []
      },
      time1aux: false,
      time2aux: false,
      time3aux: false
    };
  },
  methods: {
    addTime(time, participantes) {
      let ctx = this;
      if (
        ctx.time1aux === false &&
        ctx.time2aux === false &&
        ctx.time3aux === false
      ) {
        ctx.time1.nomeTime1 = time;
        ctx.time1.partTime1 = participantes;
        ctx.time1aux = true;
        (ctx.nomeTIME = ""), (ctx.nomesPARTICIPANTES = "");
      } else if (
        ctx.time1aux === true &&
        ctx.time2aux === false &&
        ctx.time3aux === false
      ) {
        ctx.time2.nomeTime2 = time;
        ctx.time2.partTime2 = participantes;
        ctx.time2aux = true;
        (ctx.nomeTIME = ""), (ctx.nomesPARTICIPANTES = "");
      } else if (
        ctx.time1aux === true &&
        ctx.time2aux === true &&
        ctx.time3aux === false
      ) {
        console.log("terceiro time");
        ctx.time3.nomeTime3 = time;
        ctx.time3.partTime3 = participantes;
        ctx.time3aux = true;
        (ctx.nomeTIME = ""), (ctx.nomesPARTICIPANTES = "");
      } else if (
        ctx.time1aux === true &&
        ctx.time2aux === true &&
        ctx.time3aux === true
      ) {
        console.log("heheheh");
      }

      console.log(time, participantes);
    },
    addDinheiro() {
      if (this.shape === "time1") {
        this.time1.dinheiro1 += 200;
      }
      if (this.shape === "time2") {
        this.time2.dinheiro2 += 200;
      }
      if (this.shape === "time3") {
        this.time3.dinheiro3 += 200;
      }
    },
    addAtividades() {
      this.promptAddAtividade = true;
    },
    verAtividades(adicionarAtividade) {
      if (this.shape === "time1") {
        this.time1.atividades1.push(adicionarAtividade);
      }
      if (this.shape === "time2") {
        this.time2.atividades2.push(adicionarAtividade);
      }
      if (this.shape === "time3") {
        this.time3.atividades3.push(adicionarAtividade);
      }
    },
    dinheiroTime(){
      this.promptGerenciarDinheiro = true;
    },
    gerenciarDinheiro(adicionarDinheiro) {
      console.log('time', this.time1.dinheiro1)
      if (this.shape === "time1") {
        this.time1.dinheiro1 = this.time1.dinheiro1 + parseInt(adicionarDinheiro);
      }
      if (this.shape === "time2") {
        this.time2.dinheiro2 = this.time2.dinheiro2 + parseInt(adicionarDinheiro);
      }
      if (this.shape === "time3") {
        this.time3.dinheiro3 = this.time3.dinheiro3 + parseInt(adicionarDinheiro);
      }
    },
    dado() {
      //matodo que gera um numero similar a jogar um dado
      this.dadoVal = Math.floor(Math.random() * 6 + 1);

      if (this.shape === "time1") {
        this.time1.casaTime1 += this.dadoVal;
        if (this.time1.casaTime1 > 44) {
          this.time1.casaTime1 = this.time1.casaTime1 - 44;
        }
      }
      if (this.shape === "time2") {
        this.time2.casaTime2 += this.dadoVal;
        if (this.time2.casaTime2 > 44) {
          this.time2.casaTime2 = this.time2.casaTime2 - 44;
        }
      }
      if (this.shape === "time3") {
        this.time3.casaTime3 += this.dadoVal;
        if (this.time3.casaTime3 > 44) {
          this.time3.casaTime3 = this.time3.casaTime3 - 44;
        }
      }

      console.log("dado", this.shape);
    },
    showPapeis() {
      this.mostrarPapeis1 = true;
    },
    showPapeis2() {
      this.mostrarPapeis2 = true;
    },
    showPapeis3() {
      this.mostrarPapeis3 = true;
    },
    showFerramentas() {
      this.mostrarFerramentas1 = true;
    },
    showFerramentas2() {
      this.mostrarFerramentas2 = true;
    },
    showFerramentas3() {
      this.mostrarFerramentas3 = true;
    },

    showPergunta() {
      let num = Math.floor(Math.random() * 60 + 1);
      console.log("randon", num);
      perguntas.forEach(pergunta => {
        if (pergunta.value === num) {
          this.alert("Pergunta", pergunta.label, pergunta.resposta);
          //console.log(atividade.label)
        }
      });
    },
    showSortReves() {
      //busca no enums o card de sorte ou revés
      let num = Math.floor(Math.random() * 6 + 1);
      console.log("randon", num);
      sorte_reves.forEach(sorte_reves => {
        if (sorte_reves.value === num) {
          console.log(sorte_reves.title);
          this.alert(sorte_reves.title, sorte_reves.label, sorte_reves.valor);
          //console.log(atividade.label)
        }
      });
    },
    showAtiv(label) {
      //busca no enums o card de atividades
      //console.log('label', label)
      atividades.forEach(atividade => {
        if (atividade.value === label) {
          this.alert("", atividade.label, atividade.valor);
          //console.log(atividade.label)
        }
      });
    },
    alert(title, atividade, valor) {
      //mostra na tela a atividade, sorte e revés
      this.$q
        .dialog({
          dark: true,
          title: title === "" ? "Atividade" : title,
          message: atividade
        })
        .onOk(() => {
          this.$q.dialog({
            dark: true,
            message: valor
          });
          console.log("OK");
        })
        .onCancel(() => {
          console.log("Cancel");
        });
    }
  }
};
</script>

<style>
.inputDado {
  margin-left: 10px;
  width: 120px !important;
  height: 20px !important;
}
.btn-size {
  width: 70px !important;
  height: 20px !important;
}

.btn-pergunta {
  margin-left: 10px;
  width: 100px !important;
  height: 20px !important;
}

.my-card {
  margin-top: 10px;
  width: 400px;
  height: 300px;
}
</style>

