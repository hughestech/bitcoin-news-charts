<template>
<v-layout row wrap>
  <v-flex xs12>
    <timeLine :timeline-data="timelineData"></timeLine>
  </v-flex>
</v-layout>
</template>

<script>
import TimeLine from './timeline/timeline'
import {TIME_LINE_DATA} from '../assets/TIME_LINE_BITCOIN';

export default {
  name: 'BitcoinTimeLine',
  data() {
    return {
      timelineData: TIME_LINE_DATA
    }
  },
  components: {
    TimeLine
  }
}
</script>
