Television-Media-Query-Test
===========================

An attempt to get a sense of what media queries are supported if any for the television.

The outlook does not look good, so don't expect this happening anytime soon.

Tv Support List:

<ul>
  <li>
  <strong>Google TV</strong> - No media queries worked, not even TV.
  </li>
  <li>
  <strong>Wii Opera Browser</strong> - 
  </li>
  <li>
  <strong>Apple TV</strong> - 
  </li>
</ul>

Resources:

<ul>
<li><a href="https://developers.google.com/tv/web/docs/design_for_tv">Google TV Developers</a></li>
<li><a href="http://en.wikipedia.org/wiki/File:Vector_Video_Standards4.svg">Visual of TV "Breakpoints"</a></li>
<li><a href="http://www.mhp.org/docs/itv-design_v1.pdf">Designing for Interactive TV"</a></li>
</ul>

Additional Info: 

<ul>
  <li>
  <strong>Exclusive By Spec</strong> - Media Queries are exclusive by spec. If they are implemented on Tv, they'd have to not support Screen, breaking the rest of the web on TV's.
  </li>
  <li>
  <strong>Multiple Media Queries</strong> - If they supported both, in spite of the spec, there's a cascade issue. Media types are not intended to cascade.
  </li>
</ul>


