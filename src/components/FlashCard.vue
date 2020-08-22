<template>
    <div class="container main-container" :class="inputMode">
        <form @submit="handleSubmit" id="form">
            <h3>Translate to <span>{{ this.translateMode === '1to2' ? this.language1 : this.language2 }}</span></h3>
            <h1 class="lang-from" @click="inputMode === 'Flashcard' ? showAnswerFc : ''">"{this.state.langFrom[this.state.randomNum]}"</h1>
        </form>
    </div>
</template>

<script>
export default {
  data () {
    return {
      spreadsheetID: '1DntQwj2nfvobtxkOExsSMm2DLHQNlzf2q48WhWlMqAM', // Italian
      language1: '',
      language2: '',
      langFrom: '',
      langTo: '',
      translationInputValue: '',
      wordBank: [],
      customListInputValue: '',
      currentList: '',
      // set default state values
      translateMode: '1to2',
      inputMode: 'Flashcard',
      checkAccents: false
    }
  },
  methods: {
    getData (value) {
      if (value === undefined) {
        value = this.spreadsheetID
      }
    },
    getCard () {

    },
    archiveCard () {

    },
    handleWordBank () {

    },
    keyboardModehandleChange (event) {

    },
    handleSubmit () {

    },
    switchInput (value) {

    },
    switchTranslationMode () {

    },
    showAnswerFc () {

    },
    setList (value) {

    },
    customListhandleChange (event) {

    }
  },
  beforeMount () {
    this.getData()
  },
  mounted () {

  }
}
</script>
