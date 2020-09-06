<template>
  <div>
    <h1>{{ msg }}</h1>
    <p> Before continuing please <a target="_blank" href="http://tinyurl.com/familytier">view this video</a></p>
    <p> You must acknowledge that you have reviewed our Community Guidelines and Disclaimer.</p>
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
        <div>
          <p style="text-align:center"><b>COMMUNITY GUIDELINES</b></p>
          <p> 1. This is an economic sharing community. By opting in, you are committing to giving a gift to the person in the water within 24 hours of Matrix closure. You are committing to sharing this opportunity with TRUSTED family or friends.</p>
          <p> 2. Potential Sparks that have interest in becoming Fires have to be invited to attend a presentation by a current member of the community.  Once a presentation is attended the Spark can make a decision to become a Fire.</p>
          <p> 3. New Fires are added to the boards in the community Matrix Update Chat by the administrator(s).  The Fire gives their gift to the Water when all fires spots are filled in.  The Water’s preferred methods for receiving their blessings will be provided on the gifting celebration flyer that will be posted with the closed Matrix.</p>
          <p> 4. If anyone in the Fire position breaks their commitment of blessing to the person in the water within 24 hours for reasons other than technical difficulties, that member will be removed from the group with no chance of re-entry. No exceptions are allowed.</p>
          <p> 5. Split Matrix are posted once the Water confirms that they have received all of their blessings according to the community Matrix updates schedule.</p>
          <p> 6. There are no refunds for a gift.  This is not a payment, therefore gifts are non-refundable. </p>
          <div style="text-align:center;padding-top:10px;">
            <input id="checkbox" type="checkbox" onclick="document.getElementById('agreed').disabled = false"/>
            <label style="font-size:14pt" for="checkbox">I have read, understand and agree to the community guidelines and disclaimer</label>
          </div>
        </div>
        <div style="text-align:center;padding-top:10px">
          <input class="button" disabled=true id="agreed" type="button" value="I want to join!" onclick="window.location.href='https://forms.gle/RY6oQWTT5KPvV9ba6'"/>
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
    position:-webkit-sticky;
    bottom: 25px;
    margin-left: 15%;
    margin-right: 15%;
    text-align:left;
    font-size:11pt;
}
.button {
  width: 200px;
  height: 50px;
  font-size: 18pt;
}

</style>
