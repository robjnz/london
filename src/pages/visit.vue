<template>
  <Layout>
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-16 text-4xl text-red-600">
        <span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Places to Visit
      </h1>
      

      <div class="grid sm:flex">
        <alexandra /><!--alexandra palace-->
        <bankengland /><!--bank of england museum-->
        <battersea /><!--Battersea Park-->
        </div>
      <div class="grid sm:flex">
        <batterseazoo /><!--Battersea Park Children’s Zoo-->
        <bethune /><!--Bethune Nature reserve-->
        <bexley /><!--bexleyWoods-->
        </div>
      <div class="grid sm:flex">
        <british /><!--British Museum-->
        <ashby /><!--Ashby’s Bixton windmill-->
        <brockwell /><!--Brockwell Park-->
         </div>
      <div class="grid sm:flex">
        <carlyle /> <!--Carlyle's House -->
        <chingford /><!--Chingford Sky Trail-->
        <chislehurst /><!--Chislehurst Caves-->
         </div>
      <div class="grid sm:flex">
        <churchhouse /><!--Church House Gardens-->
        <warrooms /><!--churchils War rooms-->
        <clink /><!--Clink Prison Museum-->
         </div>
      <div class="grid sm:flex">
        <minster /><!--Croydon Minster-->
        <crystalV /><!--Crystal Palace Park-->
        <deen /><!--DEEN CITY FARM-->
         </div>
      <div class="grid sm:flex">
        <demorgan /><!--De Morgan Center-->
        <design/><!--Design Museum-->
        <down /><!--Down House-->
         </div>
      <div class="grid sm:flex">
        <docklands /><!--Docklands Museum-->
        <eastbury /><!--Eastbury Manor House-->
        <elizabeth /><!--Elizabeth's Hunting Lodge-->
         </div>
      <div class="grid sm:flex">
        <eltham /><!--Eltham Palace-->
        <epping /><!--Epping Forest-->
         <emery /><!--Emery Walker’s House-->
          </div>
      <div class="grid sm:flex">
        <fairlop /><!--Fairlop Waters Park-->
        <fenton /><!--fenton house-->
        <forty /><!--forty hall-->
         </div>
      <div class="grid sm:flex">
        <freud /><!--Freud Museum-->
        <geffrye /><!--Geffrye Museum-->
        <hackney /><!--Hackney City Farm-->
         </div>
      <div class="grid sm:flex">
        <hall /><!--Hall Place & Gardens-->
        <hampstead /><!--Hampstead Heath-->
        <havering /><!--Havering Country Park-->
         </div>
      <div class="grid sm:flex">
        <robinson /><!--HEATH ROBINSON MUSEUM-->
        <belfast /><!--HMS Belfast-->
        <horniman /><!--Horniman Museam & Park-->
         </div>
      <div class="grid sm:flex">
        <hospital /><!--Hospital Chapel Ilford-->
        <house /><!--House Mill-->
        <war /><!--Imperial War Museum-->
         </div>
      <div class="grid sm:flex">
        <jack /><!--Jack The Ripper Museum-->
        <jewish /><!--jewish museum-->
        <keats /><!--Keats House -->
         </div>
      <div class="grid sm:flex">
        <kenpalace /><!--Kensington Palace-->
        <kenwood /><!--kenwood house-->
        <kew /><!--Kew Gardens -->
         </div>
      <div class="grid sm:flex">
        <lee /><!--Lee Valley-->
        <canal /><!--London canal museum-->
        <mithraeum /><!--London Mithraeum-->
         </div>
      <div class="grid sm:flex">
        <zoo /><!--london zoo-->
        <marblehouse /><!--MARBLE HILL HOUSE -->
        <markfield /><!--Markfield -->
         </div>
      <div class="grid sm:flex">
        <mayesbrook /><!--Mayesbrook Park-->
        <morden /><!--MORDEN HALL PARK-->
        <mudchute /><!--mudchute-->
         </div>
      <div class="grid sm:flex">
        <museumlondon /><!--museum of london-->
        <army /><!--National Army Museum-->
        <natural /><!-- Natural History Museum-->
        </div>
      <div class="grid sm:flex">
        <newham /><!--Newham City Farm-->
        <queen /><!--Queen Elizabeth Olympic Park-->
        <pitzhanger /><!--Pitzhanger Manor House-->
        </div>
      <div class="grid sm:flex">
        <ragged /><!--Ragged School Museum-->
        <rainham /><!--Rainham Hall-->
        <ranger /><!--Ranger’s House-->
        </div>
      <div class="grid sm:flex">
        <red /><!--Red house-->
        <regentscanal /><!--Regent’s Canal-->
        <regentspark /><!--Regent’s Park-->
        </div>
      <div class="grid sm:flex">
        <roundwood /><!--Roundwood Park-->
        <airforce /><!--Royal Air Force Museum-->
        <greenwich /><!--Royal Museums Greenwich-->
        </div>
      <div class="grid sm:flex">
        <ruislip /><!--Ruislip Woods -->
        <saatchi /> <!--Saatchi Gallery-->
        <science /><!--Science Museum-->
        </div>
      <div class="grid sm:flex">
        <serpentine /><!--Serpentine Galleries-->
        <severndroog /><!--Severndroog Castle-->
        <shirley/><!--Shirley Windmill-->
        </div>
      <div class="grid sm:flex">
        <southwarkcath /><!--Southwark Cathedral-->
        <antioch /><!--St. Margaret of Antioch-->
        <pauls /><!--St. Pauls Cathedral-->
        </div>
      <div class="grid sm:flex">
        <stephens /><!--Stephens house-->
        <sutton /><!--Sutton House-->
        <britain /><!--Tate Brittain-->
        </div>
      <div class="grid sm:flex">
        <tate /><!--Tate Modern -->
        <thames /><!--Thames Barrier-->
        <national/><!--the national Gallery-->
        </div>
      <div class="grid sm:flex">
        <operating /><!--The Old Operating Theatre-->
        <totteridge /><!--Totteridge fields-->
        <towerbridge /><!--Tower Bridge-->
        </div>
      <div class="grid sm:flex">
        <tower /><!--Tower Of London-->
        <trinity /><!--Trinity Buoy Wharf-->
        <upminster /><!--Upminster Windmill-->
        </div>
      <div class="grid sm:flex">
        <valence /><!--Valence House Museum-->
        <valentines /><!--Valentines Mansion-->
        <victoriaalbert /><!--Victoria & Albert Museum-->
        </div>
      <div class="grid sm:flex">
        <victoria /><!--Victoria Park-->
        <viktor /><!--Viktor Wyne Museum-->
        <wandsworthcommon /><!--Wandsworth Common-->
        </div>
      <div class="grid sm:flex">
        <wanstead /><!--Wansted Park-->
        <william /><!--William Morris Gallery-->
        <wimbledoncommon /><!--Wimbledon Common-->
        </div>
      <div class="grid sm:flex">
        <wimbledonmill /><!--Wimbledon Windmill-->
       </div>

       <div class="grid sm:flex">
       </div>
    <br />
    </div>
  </Layout>
</template>

<script>
import antioch from "@/components/Visit/antioch";
import bexley from "@/components/Visit/bexley";
import chingford from "@/components/Visit/chingford";
import danson from "@/components/Visit/danson";
import docklands from "@/components/Visit/docklands";
import eastbury from "@/components/Visit/eastbury";
import elizabeth from "@/components/Visit/elizabeth";
import eltham from "@/components/Visit/eltham";
import epping from "@/components/Visit/epping";
import fairlop from "@/components/Visit/fairlop";
import greenwich from "@/components/Visit/greenwich";
import geffrye from "@/components/Visit/geffrye";
import hackney from "@/components/Visit/hackney";
import hall from "@/components/Visit/hall";
import havering from "@/components/Visit/havering";
import horniman from "@/components/Visit/horniman";
import hospital from "@/components/Visit/hospital";
import house from "@/components/Visit/house";
import jack from "@/components/Visit/jack";
import lee from "@/components/Visit/lee";
import mayesbrook from "@/components/Visit/mayesbrook";
import mudchute from "@/components/Visit/mudchute";
import newham from "@/components/Visit/newham";
import queen from "@/components/Visit/queen";
import ragged from "@/components/Visit/ragged";
import rainham from "@/components/Visit/rainham";
import ranger from "@/components/Visit/ranger";
import red from "@/components/Visit/red";
import severndroog from "@/components/Visit/severndroog";
import sutton from "@/components/Visit/sutton";
import thames from "@/components/Visit/thames";
import tower from "@/components/Visit/tower";
import trinity from "@/components/Visit/trinity";
import upminster from "@/components/Visit/upminster";
import valence from "@/components/Visit/valence";
import valentines from "@/components/Visit/valentines";
import victoria from "@/components/Visit/victoria";
import viktor from "@/components/Visit/viktor";
import wanstead from "@/components/Visit/wanstead";
import william from "@/components/Visit/william";
import alexandra from "@/components/Visit/north/alexandra";
import bethune from "@/components/Visit/north/bethune";
import canal from "@/components/Visit/north/canal";
import forty from "@/components/Visit/north/forty";
import jewish from "@/components/Visit/north/jewish";
import markfield from "@/components/Visit/north/markfield";
import stephens from "@/components/Visit/north/stephens";
import airforce from "@/components/Visit/north/airforce";
import totteridge from "@/components/Visit/north/totteridge";
import fenton from "@/components/Visit/north/fenton";
import zoo from "@/components/Visit/north/zoo";
import freud from "@/components/Visit/north/freud";
import down from "@/components/Visit/down";
import crystalV from "@/components/Visit/crystalV";
import chislehurst from "@/components/Visit/chislehurst";
import churchhouse from "@/components/Visit/churchhouse";
import shirley from "@/components/Visit/shirley";
import minster from "@/components/Visit/minster";
import morden from "@/components/Visit/morden";
import wimbledonmill from "@/components/Visit/wimbledonmill";
import deen from "@/components/Visit/deen";
import wimbledoncommon from "@/components/Visit/wimbledoncommon";
import wandsworthcommon from "@/components/Visit/wandsworthcommon";
import demorgan from "@/components/Visit/demorgan";
import batterseazoo from "@/components/Visit/batterseazoo";
import battersea from "@/components/Visit/battersea";
import roundwood from "@/components/Visit/roundwood";
import pitzhanger from "@/components/Visit/pitzhanger";
import emery from "@/components/Visit/emery";
import robinson from "@/components/Visit/robinson";
import ruislip from "@/components/Visit/ruislip";
import marblehouse from "@/components/Visit/marblehouse";
import kew from "@/components/Visit/kew";
import museumlondon from "@/components/Visit/museumlondon";
import bankengland from "@/components/Visit/bankengland";
import mithraeum from "@/components/Visit/mithraeum";
import pauls from "@/components/Visit/pauls";
import towerbridge from "@/components/Visit/towerbridge";
import british from "@/components/Visit/british";
import hampstead from "@/components/Visit/hampstead";
import kenwood from "@/components/Visit/kenwood";
import regentspark from "@/components/Visit/regentspark";
import keats from "@/components/Visit/keats";
import regentscanal from "@/components/Visit/regentscanal";
import victoriaalbert from "@/components/Visit/victoriaalbert";
import natural from "@/components/Visit/natural";
import science from "@/components/Visit/science";
import kenpalace from "@/components/Visit/kenpalace";
import design from "@/components/Visit/design";
import serpentine from "@/components/Visit/serpentine";
import saatchi from "@/components/Visit/saatchi";
import army from "@/components/Visit/army";
import carlyle from "@/components/Visit/carlyle";
import brockwell from "@/components/Visit/brockwell";
import ashby from "@/components/Visit/ashby";
import tate from "@/components/Visit/tate";
import southwarkcath from "@/components/Visit/southwarkcath";
import war from "@/components/Visit/war";
import belfast from "@/components/Visit/belfast";
import operating from "@/components/Visit/operating";
import clink from "@/components/Visit/clink";
import warrooms from "@/components/Visit/warrooms";
import britain from "@/components/Visit/britain";
import national from "@/components/Visit/national";

import date from "@/components/Home/date";

export default {
  metaInfo: {
    title: "Visit",
    meta : [
      {
        name   : "description",
        content: 
          "Visit Places Of Historical And Local Interest In London for Day Out."
      }
    ]
  },
  components: {
    antioch,
    bexley,
    chingford,
    danson,
    docklands,
    eastbury,
    elizabeth,
    eltham,
    epping,
    fairlop,
    greenwich,
    geffrye,
    hackney,
    hall,
    havering,
    horniman,
    hospital,
    house,
    jack,
    lee,
    mayesbrook,
    mudchute,
    newham,
    queen,
    ragged,
    rainham,
    ranger,
    red,
    severndroog,
    sutton,
    thames,
    tower,
    trinity,
    upminster,
    valence,
    valentines,
    victoria,
    viktor,
    wanstead,
    william,
    alexandra,
    bethune,
    canal,
    forty,
    jewish,
    markfield,
    stephens,
    totteridge,
    airforce,
    fenton,
    zoo,
    freud,
    down,
    crystalV,
    chislehurst,
    churchhouse,
    shirley,
    minster,
    morden,
    wimbledonmill,
    deen,
    wimbledoncommon,
    wandsworthcommon,
    demorgan,
    batterseazoo,
    battersea,
    roundwood,
    pitzhanger,
    emery,
    robinson,
    ruislip,
    marblehouse,
    kew,
    museumlondon,
    bankengland,
    mithraeum,
    pauls,
    towerbridge,
    british,
    hampstead,
    kenwood,
    regentspark,
    keats,
    regentscanal,
    victoriaalbert,
    natural,
    science,
    kenpalace,
    design,
    serpentine,
    saatchi,
    army,
    carlyle,
    brockwell,
    ashby,
    tate,
    southwarkcath,
    war,
    belfast,
    operating,
    clink,
    warrooms,
    britain,
    national,
    date,
  }
};
</script>
