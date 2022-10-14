---
{"dg-publish":true,"permalink":"/vrc-projects/hidden-vr-chat-worlds/zombie-infection-neo-tokyo-quest/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true}
---

# [Zombie Infection - NeoTokyo (Quest)](https://vrchat.com/home/world/wrld_0e6b77e6-ce49-425f-9b9a-4fc3978c5dd4)
<div
  style="
    border: 1px solid rgb(222, 222, 222);
    box-shadow: rgba(0, 0, 0, 0.06) 0px 1px 3px;
  "
>
  <div class="w __if _lc _sm _od _alsd _alcd _lh14 _xm _xi _ts _dm">
    <div class="wf">
      <div class="wc">
        <div class="e" style="padding-bottom: 100%">
          <div class="em">
            <a
              href="https://vrchat.com/home/world/wrld_0e6b77e6-ce49-425f-9b9a-4fc3978c5dd4"
              target="_blank"
              rel="noopener"
              data-do-not-bind-click
              class="c"
              style="
                background-image: url('https://api.vrchat.cloud/api/1/file/file_e8acb4b0-1b99-4258-9402-5e72040ed646/2/file');
              "
            ></a>
          </div>
        </div>
      </div>
      <div class="wt">
        <div class="t _f0 _ffsa _fsn _fwn">
          <div class="th _f1p _fsn _fwb">
            <a href="https://vrchat.com/home/world/wrld_0e6b77e6-ce49-425f-9b9a-4fc3978c5dd4" target="_blank" rel="noopener" class="thl"
              >Zombie Infection Quest by MMMaellon</a
            >
          </div>
          <div class="td">Zombie Infection Quest</div>
          <div class="tf _f1m">
            <div class="tc">
              <a href="https://vrchat.com/home/world/wrld_0e6b77e6-ce49-425f-9b9a-4fc3978c5dd4" target="_blank" rel="noopener" class="tw _f1m"
                ><span class="twt">https://vrchat.com/home/world/wrld_0e6b77e6-ce49-425f-9b9a-4fc3978c5dd4</span
                ><span class="twd">https://vrchat.com/home/world/wrld_0e6b77e6-ce49-425f-9b9a-4fc3978c5dd4</span></a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>


I'm having lots of trouble getting it optimized enough for Quest. Right now, I average 30 fps in an empty lobby :(

I was trying to pioneer a new optimization where I condense many different textures into one with texture arrays. This would allow me to have one material for many different meshes without atlassing. The reason why I didn't want to atlas my textures was because there's a lot of tiling on this map.

Unity was able to batch all the merged materials into one batchcall, but unfortunately the fps didn't improve. I also deleted all the Udon scripts to make sure they weren't the source of the lag, so I suspect texture arrays come with their own overhead.