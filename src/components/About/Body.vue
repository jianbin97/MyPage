 <template>
  <div class="body">
    <span id='text1'>{{text1}}</span>
    <p id='info1'>{{info1}}</p>
    <p id='info2'>{{info2}}</p>
    <span id='text2'>{{text2}}</span>

    <span id='nic'>{{nic}}</span>
    <span id='n1'>{{n1}}</span>
    <span id='arn'>{{arn}}</span>
    <span id='a1'>{{a1}}</span>
    <span id='jb'>{{jb}}</span>
    <span id='j1'>{{j1}}</span>
    <span id='char'>{{char}}</span>
    <span id='c1'>{{c1}}</span>
    <span id='jia'>{{jia}}</span>
    <span id='j2'>{{j2}}</span>
    <span id='vic'>{{vic}}</span>
    <span id='v1'>{{v1}}</span>

  </div>
</template>

<script>
export default {
  data() {
      return {
        text1: 'What We Do \n',
        info1: '(Website) is a platform for beginners to gain \n exposure to coding and enjoy the fun in coding \n through our interactive exercises. \n',
        info2: 'We believe that any individual who has a keen \n mind in learning can definitely become a Coder',
        text2: 'Who We Are',

        nic: 'Nicole',
        n1: 'Pro coder',
        arn: 'Arnold',
        a1: 'Nerd',
        jb: 'Jian Bin',
        j1: 'SOC struggler',
        char: 'Charlotte',
        c1: 'Leader',
        jia: 'Jia Xuan',
        j2: 'Follower',
        vic: 'Vicki',
        v1: 'The Serious One'
      }
  }
}
</script>

<style scoped>
    #text1{
        position: absolute;
        width: 182px;
        height: 36px;
        left: 245px;
        top: 280px;

        font-family: Futura Hv BT;
        font-style: normal;
        font-weight: 900;
        font-size: 30px;
        line-height: 36px;
        /* identical to box height */

        display: flex;
        align-items: center;
    }

    #info1{
        position: absolute;
        width: 607px;
        height: 446px;
        left: 66px;
        top: 340px;

        font-family: Futura Hv BT;
        font-style: normal;
        font-weight: 900;
        font-size: 25px;
        line-height: 30px;

        color: #000000;

        mix-blend-mode: darken;
    }

    #info2{
        position: absolute;
        width: 607px;
        height: 446px;
        left: 66px;
        top: 480px;

        font-family: Futura Hv BT;
        font-style: normal;
        font-weight: 900;
        font-size: 25px;
        line-height: 30px;

        color: #000000;

        mix-blend-mode: darken;
    }

    #text2{
        position: absolute;
        width: 481px;
        height: 150px;
        left: 979px;
        top: 630px;

        font-family: Futura Hv BT;
        font-style: normal;
        font-weight: 900;
        font-size: 30px;
        line-height: 36px;
        display: flex;
        align-items: center;

        color: #000000;
    }

    #nic{
        position: absolute;
        width: 94px;
        height: 56px;
        left: 790px;
        top: 880px;

        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 30px;
        line-height: 35px;

        color: #000000;
    }

    #n1{
        position: absolute;
        
        width: 94px;
        height: 56px;
        left: 793px;
        top: 930px;

        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 20px;
        line-height: 23px;

        color: #000000;
    }

    #arn{
        position: absolute;
        width: 98px;
        height: 56px;
        left: 1026px;
        top: 880px;

        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 30px;
        line-height: 35px;
        text-align: center;

        color: #000000;
    }

    #a1{
        position: absolute;
        width: 98px;
        height: 56px;
        left: 1026px;
        top: 930px;
        
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 20px;
        line-height: 23px;
        text-align: center; 

        color: #000000;
    }

    #jb{
        position: absolute;
        width: 123px;
        height: 56px;
        left: 1252px;
        top: 880px;

        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 30px;
        line-height: 35px;
        text-align: center;

        color: #000000;
    }

    #j1{

        position: absolute;
        width: 123px;
        height: 56px;
        left: 1252px;
        top: 930px;

        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 20px;
        line-height: 23px;
        text-align: center;

        color: #000000;
    }

    #char{
        position: absolute;
        width: 125px;
        height: 56px;
        left: 772px;
        top: 1120px;

        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 30px;
        line-height: 35px;
        text-align: center;

        color: #000000;
    }

    #c1{
        position: absolute;
        width: 125px;
        height: 56px;
        left: 772px;
        top: 1170px;

        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 20px;
        line-height: 23px;
        text-align: center;

        color: #000000
    }

    #jia{
        position: absolute;
        width: 120px;
        height: 56px;
        left: 1018px;
        top: 1120px;

        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 30px;
        line-height: 35px;
        text-align: center;

        color: #000000;
    }

    #j2{
        position: absolute;
        width: 117px;
        height: 56px;
        left: 1018px;
        top: 1170px;

        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 20px;
        line-height: 23px;
        text-align: center;

        color: #000000;
    }

    #vic{
        position: absolute;
        width: 146px;
        height: 56px;
        left: 1241px;
        top: 1120px;

        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 30px;
        line-height: 35px;
        text-align: center;

        color: #000000;
    }

    #v1{
        position: absolute;
        width: 146px;
        height: 56px;
        left: 1241px;
        top: 1170px;

        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 20px;
        line-height: 23px;
        text-align: center;

        color: #000000;
    }


</style>