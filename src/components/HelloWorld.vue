<template>
  <div>
    <h1>{{ msg }}</h1>
    <p> Before you signup, you must acknowledge that you have reviewed our Community Guidelines</p>
    <p> These guidelines can be found <button class="btn" >Coming Soon</button></p>
    <!--<input id="checkbox" type="checkbox"/>
    <label for="checkbox">I have read, understand and agree to the community guidelines</label>-->
    <p> Goto <a  id="signup" href="https://forms.gle/RY6oQWTT5KPvV9ba6">Friends and Family Tier Group Signup</a> </p>
      <div id="bottom">
        <div>
          <p style="text-align:center"><b>DISCLAIMER</b></p>
          The information shown in the presentation should not be taken as legal advice.  Team
          Overflow is not the originator or owner of this concept. Our only objective in this
          presentation is to share the economics of community sharing and giving that was shared with
          us for the holistic benefit of our community.  The illustrations shown are only potential
          outcomes and in no way are being relayed as guaranteed outcomes. Please note that timeframes
          presented for receipt of gifts are only hypothetical and vary based on the collaborative
          efforts of the entire private community.
        </div>
      </div>
  </div>

</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component
export default class HelloWorld extends Vue {
  @Prop() private msg!: string
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

#bottom{
    position: absolute;
    bottom: 25px;
    margin-left: 25%;
    margin-right: 25%;
    text-align:left;
    font-size:11pt;
}

</style>
