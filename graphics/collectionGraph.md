%!PS-Adobe-3.0 EPSF-3.0
%%Creator: Mayura Draw, Version 4.3
%%Title: collectionGraph.md
%%CreationDate: Sat Dec 08 15:49:44 2007
%%BoundingBox: -5 677 209 792
%%DocumentFonts: TimesNewRomanPSMT
%%Orientation: Portrait
%%EndComments
%%BeginProlog
%%BeginResource: procset MayuraDraw_ops
%%Version: 4.3
%%Copyright: (c) 1993-2003 Mayura Software
/PDXDict 100 dict def
PDXDict begin
% width height matrix proc key cache
% definepattern -\> font
/definepattern { %def
  7 dict begin
    /FontDict 9 dict def
    FontDict begin
      /cache exch def
      /key exch def
      /proc exch cvx def
      /mtx exch matrix invertmatrix def
      /height exch def
      /width exch def
      /ctm matrix currentmatrix def
      /ptm matrix identmatrix def
      /str
      (xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)
      def
    end
    /FontBBox [ %def
      0 0 FontDict /width get
      FontDict /height get
    ] def
    /FontMatrix FontDict /mtx get def
    /Encoding StandardEncoding def
    /FontType 3 def
    /BuildChar { %def
      pop begin
      FontDict begin
        width 0 cache { %ifelse
          0 0 width height setcachedevice
        }{ %else
          setcharwidth
        } ifelse
        0 0 moveto width 0 lineto
        width height lineto 0 height lineto
        closepath clip newpath
        gsave proc grestore
      end end
    } def
    FontDict /key get currentdict definefont
  end
} bind def

% dict patternpath -
% dict matrix patternpath -
/patternpath { %def
  dup type /dicttype eq { %ifelse
    begin FontDict /ctm get setmatrix
  }{ %else
    exch begin FontDict /ctm get setmatrix
    concat
  } ifelse
  currentdict setfont
  FontDict begin
    FontMatrix concat
    width 0 dtransform
    round width div exch round width div exch
    0 height dtransform
    round height div exch
    round height div exch
    0 0 transform round exch round exch
    ptm astore setmatrix

    pathbbox
    height div ceiling height mul 4 1 roll
    width div ceiling width mul 4 1 roll
    height div floor height mul 4 1 roll
    width div floor width mul 4 1 roll

    2 index sub height div ceiling cvi exch
    3 index sub width div ceiling cvi exch
    4 2 roll moveto

    FontMatrix ptm invertmatrix pop
    { %repeat
      gsave
        ptm concat
        dup str length idiv { %repeat
          str show
        } repeat
        dup str length mod str exch
        0 exch getinterval show
      grestore
      0 height rmoveto
    } repeat
    pop
  end end
} bind def

% dict patternfill -
% dict matrix patternfill -
/patternfill { %def
  gsave
    eoclip patternpath
  grestore
  newpath
} bind def

/img { %def
  gsave
  /imgh exch def
  /imgw exch def
  concat
  imgw imgh 8
  [imgw 0 0 imgh neg 0 imgh]
  /colorstr 768 string def
  /colorimage where {
    pop
    { currentfile colorstr readhexstring pop }
    false 3 colorimage
  }{
    /graystr 256 string def
    {
      currentfile colorstr readhexstring pop
      length 3 idiv
      dup 1 sub 0 1 3 -1 roll
      {
        graystr exch
        colorstr 1 index 3 mul get 30 mul
        colorstr 2 index 3 mul 1 add get 59 mul
        colorstr 3 index 3 mul 2 add get 11 mul
        add add 100 idiv
        put
      } for
      graystr 0 3 -1 roll getinterval
    } image
  } ifelse
  grestore
} bind def

/arrowhead {
  gsave
    [] 0 setdash
    strokeC strokeM strokeY strokeK setcmykcolor
    2 copy moveto
    4 2 roll exch 4 -1 roll exch
    sub 3 1 roll sub
    exch atan rotate dup scale
    arrowtype
    dup 0 eq {
      -1 2 rlineto 7 -2 rlineto -7 -2 rlineto
      closepath fill
    } if
    dup 1 eq {
      0 3 rlineto 9 -3 rlineto -9 -3 rlineto
      closepath fill
    } if
    dup 2 eq {
      -6 -6 rmoveto 6 6 rlineto -6 6 rlineto
      -1.4142 -1.4142 rlineto 4.5858 -4.5858 rlineto
      -4.5858 -4.5858 rlineto closepath fill
    } if
    dup 3 eq {
      -6 0 rmoveto -1 2 rlineto 7 -2 rlineto -7 -2 rlineto
      closepath fill
    } if
    dup 4 eq {
      -9 0 rmoveto 0 3 rlineto 9 -3 rlineto -9 -3 rlineto
      closepath fill
    } if
    dup 5 eq {
      currentpoint newpath 3 0 360 arc
      closepath fill
    } if
    dup 6 eq {
      2.5 2.5 rmoveto 0 -5 rlineto -5 0 rlineto 0 5 rlineto
      closepath fill
    } if
    pop
  grestore
} bind def

/setcmykcolor where { %ifelse
  pop
}{ %else
  /setcmykcolor {
     /black exch def /yellow exch def
     /magenta exch def /cyan exch def
     cyan black add dup 1 gt { pop 1 } if 1 exch sub
     magenta black add dup 1 gt { pop 1 } if 1 exch sub
     yellow black add dup 1 gt { pop 1 } if 1 exch sub
     setrgbcolor
  } bind def
} ifelse

/RE { %def
  findfont begin
  currentdict dup length dict begin
    { %forall
      1 index /FID ne { def } { pop pop } ifelse
    } forall
    /FontName exch def dup length 0 ne { %if
      /Encoding Encoding 256 array copy def
      0 exch { %forall
        dup type /nametype eq { %ifelse
          Encoding 2 index 2 index put
          pop 1 add
        }{ %else
          exch pop
        } ifelse
      } forall
    } if pop
  currentdict dup end end
  /FontName get exch definefont pop
} bind def

/spacecount { %def
  0 exch
  ( ) { %loop
    search { %ifelse
      pop 3 -1 roll 1 add 3 1 roll
    }{ pop exit } ifelse
  } loop
} bind def

/WinAnsiEncoding [
  39/quotesingle 96/grave 130/quotesinglbase/florin/quotedblbase
  /ellipsis/dagger/daggerdbl/circumflex/perthousand
  /Scaron/guilsinglleft/OE 145/quoteleft/quoteright
  /quotedblleft/quotedblright/bullet/endash/emdash
  /tilde/trademark/scaron/guilsinglright/oe/dotlessi
  159/Ydieresis 164/currency 166/brokenbar 168/dieresis/copyright
  /ordfeminine 172/logicalnot 174/registered/macron/ring
  177/plusminus/twosuperior/threesuperior/acute/mu
  183/periodcentered/cedilla/onesuperior/ordmasculine
  188/onequarter/onehalf/threequarters 192/Agrave/Aacute
  /Acircumflex/Atilde/Adieresis/Aring/AE/Ccedilla
  /Egrave/Eacute/Ecircumflex/Edieresis/Igrave/Iacute
  /Icircumflex/Idieresis/Eth/Ntilde/Ograve/Oacute
  /Ocircumflex/Otilde/Odieresis/multiply/Oslash
  /Ugrave/Uacute/Ucircumflex/Udieresis/Yacute/Thorn
  /germandbls/agrave/aacute/acircumflex/atilde/adieresis
  /aring/ae/ccedilla/egrave/eacute/ecircumflex
  /edieresis/igrave/iacute/icircumflex/idieresis
  /eth/ntilde/ograve/oacute/ocircumflex/otilde
  /odieresis/divide/oslash/ugrave/uacute/ucircumflex
  /udieresis/yacute/thorn/ydieresis
] def

/SymbolEncoding [
  32/space/exclam/universal/numbersign/existential/percent
  /ampersand/suchthat/parenleft/parenright/asteriskmath/plus
  /comma/minus/period/slash/zero/one/two/three/four/five/six
  /seven/eight/nine/colon/semicolon/less/equal/greater/question
  /congruent/Alpha/Beta/Chi/Delta/Epsilon/Phi/Gamma/Eta/Iota
  /theta1/Kappa/Lambda/Mu/Nu/Omicron/Pi/Theta/Rho/Sigma/Tau
  /Upsilon/sigma1/Omega/Xi/Psi/Zeta/bracketleft/therefore
  /bracketright/perpendicular/underscore/radicalex/alpha
  /beta/chi/delta/epsilon/phi/gamma/eta/iota/phi1/kappa/lambda
  /mu/nu/omicron/pi/theta/rho/sigma/tau/upsilon/omega1/omega
  /xi/psi/zeta/braceleft/bar/braceright/similar
  161/Upsilon1/minute/lessequal/fraction/infinity/florin/club
  /diamond/heart/spade/arrowboth/arrowleft/arrowup/arrowright
  /arrowdown/degree/plusminus/second/greaterequal/multiply
  /proportional/partialdiff/bullet/divide/notequal/equivalence
  /approxequal/ellipsis/arrowvertex/arrowhorizex/carriagereturn
  /aleph/Ifraktur/Rfraktur/weierstrass/circlemultiply
  /circleplus/emptyset/intersection/union/propersuperset
  /reflexsuperset/notsubset/propersubset/reflexsubset/element
  /notelement/angle/gradient/registerserif/copyrightserif
  /trademarkserif/product/radical/dotmath/logicalnot/logicaland
  /logicalor/arrowdblboth/arrowdblleft/arrowdblup/arrowdblright
  /arrowdbldown/lozenge/angleleft/registersans/copyrightsans
  /trademarksans/summation/parenlefttp/parenleftex/parenleftbt
  /bracketlefttp/bracketleftex/bracketleftbt/bracelefttp
  /braceleftmid/braceleftbt/braceex
  241/angleright/integral/integraltp/integralex/integralbt
  /parenrighttp/parenrightex/parenrightbt/bracketrighttp
  /bracketrightex/bracketrightbt/bracerighttp/bracerightmid
  /bracerightbt
] def

/patarray [
/leftdiagonal /rightdiagonal /crossdiagonal /horizontal
/vertical /crosshatch /fishscale /wave /brick
] def
/arrowtype 0 def
/fillC 0 def /fillM 0 def /fillY 0 def /fillK 0 def
/strokeC 0 def /strokeM 0 def /strokeY 0 def /strokeK 1 def
/pattern -1 def
/mat matrix def
/mat2 matrix def
/nesting 0 def
/deferred /N def
/c /curveto load def
/c2 { pop pop c } bind def
/C /curveto load def
/C2 { pop pop C } bind def
/e { gsave concat 0 0 moveto } bind def
/F {
  nesting 0 eq { %ifelse
    pattern -1 eq { %ifelse
      fillC fillM fillY fillK setcmykcolor eofill
    }{ %else
      gsave fillC fillM fillY fillK setcmykcolor eofill grestore
      0 0 0 1 setcmykcolor
      patarray pattern get findfont patternfill
    } ifelse
  }{ %else
    /deferred /F def
  } ifelse
} bind def
/f { closepath F } bind def
/K { /strokeK exch def /strokeY exch def
     /strokeM exch def /strokeC exch def } bind def
/k { /fillK exch def /fillY exch def
     /fillM exch def /fillC exch def } bind def
/opc { pop } bind def
/Opc { pop } bind def
/L /lineto load def
/L2 { pop pop L } bind def
/m /moveto load def
/m2 { pop pop m } bind def
/n /newpath load def
/N {
  nesting 0 eq { %ifelse
    newpath
  }{ %else
    /deferred /N def
  } ifelse
} def
/S {
  nesting 0 eq { %ifelse
    strokeC strokeM strokeY strokeK setcmykcolor stroke
  }{ %else
    /deferred /S def
  } ifelse
} bind def
/s { closepath S } bind def
/Tx { fillC fillM fillY fillK setcmykcolor show
      0 leading neg translate 0 0 moveto } bind def
/T { grestore } bind def
/TX { pop } bind def
/Ts { pop } bind def
/tal { pop } bind def
/tld { pop } bind def
/tbx { pop exch pop sub /jwidth exch def } def
/tpt { %def
  fillC fillM fillY fillK setcmykcolor
  moveto show
} bind def
/tpj { %def
  fillC fillM fillY fillK setcmykcolor
  moveto
  dup stringwidth pop
  3 -1 roll
  exch sub
  1 index spacecount
  dup 0 eq { %ifelse
    pop pop show
  }{ %else
    div 0 8#040 4 -1 roll widthshow
  } ifelse
} bind def
/u {} def
/U {} def
/*u { /nesting nesting 1 add def } def
/*U {
  /nesting nesting 1 sub def
  nesting 0 eq {
    deferred cvx exec
  } if
} def
/w /setlinewidth load def
/d /setdash load def
/B {
  nesting 0 eq { %ifelse
    gsave F grestore S
  }{ %else
    /deferred /B def
  } ifelse
} bind def
/b { closepath B } bind def
/z { /align exch def pop /leading exch def exch findfont
     exch scalefont setfont } bind def
/tfn { exch findfont
     exch scalefont setfont } bind def
/Pat { /pattern exch def } bind def
/cm { 6 array astore concat } bind def
/q { mat2 currentmatrix pop } bind def
/Q { mat2 setmatrix } bind def
/Ah {
  pop /arrowtype exch def
  currentlinewidth 5 1 roll arrowhead
} bind def
/Arc {
  mat currentmatrix pop
    translate scale 0 0 1 5 -2 roll arc
  mat setmatrix
} bind def
/Arc2 { pop pop Arc } bind def
/Bx {
  mat currentmatrix pop
    concat /y1 exch def /x1 exch def /y2 exch def /x2 exch def
    x1 y1 moveto x1 y2 lineto x2 y2 lineto x2 y1 lineto
  mat setmatrix
} bind def
/Rr {
  mat currentmatrix pop
    concat /yrad exch def /xrad exch def
    2 copy gt { exch } if /x2 exch def /x1 exch def
    2 copy gt { exch } if /y2 exch def /y1 exch def
    x1 xrad add y2 moveto
    matrix currentmatrix x1 xrad add y2 yrad sub translate xrad yrad scale
    0 0 1 90 -180 arc setmatrix
    matrix currentmatrix x1 xrad add y1 yrad add translate xrad yrad scale
    0 0 1 180 270 arc setmatrix
    matrix currentmatrix x2 xrad sub y1 yrad add translate xrad yrad scale
    0 0 1 270 0 arc setmatrix
    matrix currentmatrix x2 xrad sub y2 yrad sub translate xrad yrad scale
    0 0 1 0 90 arc setmatrix
    closepath
  mat setmatrix
} bind def
/Ov {
  mat currentmatrix pop
    concat translate scale 1 0 moveto 0 0 1 0 360 arc closepath
  mat setmatrix
} bind def
end
%%EndResource
%%EndProlog
%%BeginSetup
%PDX g 3 3 0 0
%%IncludeFont: TimesNewRomanPSMT
PDXDict begin
%%EndSetup
%%Page: 1 1
%%BeginPageSetup
/_PDX_savepage save def

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 15 7.5 lineto
  0 7.5 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/rightdiagonal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 0 7.5 lineto
  15 7.5 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/leftdiagonal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 15 7.5 lineto
  2 setlinewidth stroke
} bind
/horizontal true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  7.5 0 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/vertical true definepattern pop

15 15 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 15 7.5 lineto
  7.5 0 moveto 7.5 15 lineto
  2 setlinewidth stroke
} bind
/crosshatch true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 setlinecap
  0 7.5 moveto 30 7.5 lineto
  0 22.5 moveto 30 22.5 lineto
  7.5 0 moveto 7.5 7.5 lineto
  7.5 22.5 moveto 7.5 30 lineto
  22.5 7.5 moveto 22.5 22.5 lineto
  1 setlinewidth stroke
} bind
/brick true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 2 scale
  2 setlinecap
  7.5 0 moveto 15 7.5 lineto
  0 7.5 moveto 7.5 15 lineto
  7.5 0 moveto 0 7.5 lineto
  15 7.5 moveto 7.5 15 lineto
  0.5 setlinewidth stroke
} bind
/crossdiagonal true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  2 2 scale
  1 setlinecap
  0 7.5 moveto 0 15 7.5 270 360 arc
  7.5 15 moveto 15 15 7.5 180 270 arc
  0 7.5 moveto 7.5 7.5 7.5 180 360 arc
  0.5 setlinewidth stroke
} bind
/fishscale true definepattern pop

30 30 [300 72 div 0 0 300 72 div 0 0]
{ %definepattern
  1 setlinecap 0.5 setlinewidth
  7.5 0 10.6 135 45 arcn
  22.5 15 10.6 225 315 arc
  stroke
  7.5 15 10.6 135 45 arcn
  22.5 30 10.6 225 315 arc
  stroke
} bind
/wave true definepattern pop

WinAnsiEncoding /_TimesNewRomanPSMT /TimesNewRomanPSMT RE

newpath 2 setlinecap 0 setlinejoin 2 setmiterlimit
[] 0 setdash
-5 677 moveto -5 792 lineto 209 792 lineto 209 677 lineto closepath clip
newpath
%%EndPageSetup
[0.9999 -0.01435 0.01435 0.9999 -92.86 50.69] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 0.0588235 0 k
/_TimesNewRomanPSMT 10 tfn
(P2) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -21.89 90.35] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P8) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -94.34 106.6] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P4) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -65.34 50.25] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
-1.42109e-016 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P1) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -93.75 79.12] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 0.215686 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P3) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -74.86 97.53] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 0.0588235 0 k
/_TimesNewRomanPSMT 10 tfn
(P5) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -57.91 115.2] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
-1.42109e-016 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P6) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -42.42 93.42] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 0.215686 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P7) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 79.24 74.63] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 0.0588235 0 k
/_TimesNewRomanPSMT 10 tfn
(P15) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -31.92 118.3] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P18) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -6.753 49.23] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P11) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -42.56 69.29] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P9) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 59.52 112.3] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 0.215686 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P22) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 78.9 48.89] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P14) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -4.62 125.5] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P17) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -34.8 49.22] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P10) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 22.69 48.82] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P12) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 51.75 48.58] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
-1.42109e-016 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P13) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 78.09 128.4] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P16) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 1.936 99.71] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P19) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 35.39 96.28] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P21) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 50.52 70.89] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P23) 95.437 647.003 tpt
T
[0.9999 -0.01435 0.01435 0.9999 12.45 80.79] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
-1.42109e-016 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P20) 95.437 647.003 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 4.185 -9.898] Ov
s
1 0.215686 1 0 K
7.42966 7.42966 7.27574 763.062 [1 0 0 1 54.84 -23.67] Ov
s
7.42966 7.42966 7.27574 763.062 [1 0 0 1 62.66 -67.46] Ov
s
7.42966 7.42966 7.27574 763.062 [1 0 0 1 92.38 7.754] Ov
s
7.42966 7.42966 7.27574 763.062 [1 0 0 1 156.3 -5.308] Ov
s
7.42966 7.42966 7.27574 763.062 [1 0 0 1 176.3 -67.67] Ov
s
[0.9999 -0.01435 0.01435 0.9999 61.72 83.02] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
-1.42109e-016 1 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P24) 95.437 647.003 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
-1.42109e-016 1 1 0 K
7.42966 7.42966 7.27574 763.062 [1 0 0 1 32.88 -66.8] Ov
s
1 1 0.0588235 0 K
7.42966 7.42966 7.27574 763.062 [1 0 0 1 5.28 -65.95] Ov
s
1 1 1 0 K
7.42966 7.42966 7.27574 763.062 [1 0 0 1 55.07 -48.03] Ov
s
0.5 w
q
1 0 0 1 0 0 cm
29.3281 696.118 32.3281 696.118 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 0 0 cm
20.6641 696.118 32.3281 696.118 3 1 Ah
Q
1 0.215686 1 0 K
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 4.427 -37.5] Ov
s
1 1 1 0 K
0.5 w
q
1 0 0 1 0.8535 -0.569 cm
11.5605 718.023 m
11.5605 708.221 11.5605 705.221 L2
Q
S
q
1 0 0 1 0.8535 -0.569 cm
11.5605 718.023 11.5605 705.221 3 2 Ah
Q
q
1 0 0 1 0.1422 27.6 cm
11.5605 718.023 m
11.5605 708.221 11.5605 705.221 L2
Q
S
q
1 0 0 1 0.1422 27.6 cm
11.5605 718.023 11.5605 705.221 3 2 Ah
Q
1 1 0.0588235 0 K
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 22.63 -19.58] Ov
s
1 1 1 0 K
0.5 w
q
1 0 0 1 6.117 24.47 cm
18.5305 713.472 m
13.4964 707.513 11.5605 705.221 L2
Q
S
q
1 0 0 1 6.117 24.47 cm
18.5305 713.472 11.5605 705.221 3 2 Ah
Q
-1.42109e-016 1 1 0 K
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 39.13 -1.939] Ov
s
1 1 1 0 K
0.5 w
q
1 0 0 1 23.97 43.53 cm
17.1791 712.049 m
13.4667 707.538 11.5605 705.221 L2
Q
S
q
1 0 0 1 23.97 43.53 cm
17.1791 712.049 11.5605 705.221 3 2 Ah
Q
q
1 0 0 1 6.899 50.92 cm
31.9725 709.204 m
14.505 705.796 11.5605 705.221 L2
Q
S
q
1 0 0 1 6.899 50.92 cm
31.9725 709.204 11.5605 705.221 3 2 Ah
Q
q
1 0 0 1 39.33 49.5 cm
17.7481 696.118 m
13.247 702.74 11.5605 705.221 L2
Q
S
q
1 0 0 1 39.33 49.5 cm
17.7481 696.118 11.5605 705.221 3 2 Ah
Q
q
1 0 0 1 51.1 26.6 cm
11.6672 696.26 m
11.5962 702.221 11.5605 705.221 L2
Q
S
q
1 0 0 1 51.1 26.6 cm
11.6672 696.26 11.5605 705.221 3 2 Ah
Q
q
1 0 0 1 27.31 -0.1423 cm
31.8886 696.006 34.8885 695.976 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 27.31 -0.1423 cm
20.6641 696.118 34.8885 695.976 3 1 Ah
Q
q
1 0 0 1 24.04 5.655 cm
30.0703 703.172 32.4704 704.972 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 24.04 5.655 cm
20.6641 696.118 32.4704 704.972 3 1 Ah
Q
1 1 0.0588235 0 K
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 75.26 -27.26] Ov
s
1 1 1 0 K
0.5 w
q
1 0 0 1 47.44 23.59 cm
28.0311 703.814 30.1056 705.981 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 47.44 23.59 cm
20.6641 696.118 30.1056 705.981 3 1 Ah
Q
1 1 0.0588235 0 K
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 91.48 -67.66] Ov
s
1 1 1 0 K
0.5 w
q
1 0 0 1 57.04 -0.8885 cm
31.8886 696.006 34.8885 695.976 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 57.04 -0.8885 cm
20.6641 696.118 34.8885 695.976 3 1 Ah
Q
1 1 0.0588235 0 K
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 65.59 0.6216] Ov
s
1 1 1 0 K
7.42966 7.42966 7.27574 763.062 [1 0 0 1 98.59 -17.87] Ov
s
0.5 w
q
1 0 0 1 67.81 46.44 cm
11.6672 696.26 m
6.73907 706.976 5.48565 709.702 L2
Q
S
q
1 0 0 1 67.81 46.44 cm
11.6672 696.26 5.48565 709.702 3 2 Ah
Q
q
1 0 0 1 33.18 53.5 cm
31.9725 709.204 m
24.051 708.782 21.0553 708.622 L2
Q
S
q
1 0 0 1 33.18 53.5 cm
31.9725 709.204 21.0553 708.622 3 2 Ah
Q
q
1 0 0 1 69.1 42.24 cm
27.913 699.323 30.6568 700.536 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 69.1 42.24 cm
20.6641 696.118 30.6568 700.536 3 1 Ah
Q
q
1 0 0 1 60.01 60.57 cm
31.9725 709.204 m
22.751 707.067 19.8284 706.39 L2
Q
S
q
1 0 0 1 60.01 60.57 cm
31.9725 709.204 19.8284 706.39 3 2 Ah
Q
q
1 0 0 1 66.88 53.7 cm
31.9725 709.204 m
34.4147 702.42 35.4308 699.597 L2
Q
S
q
1 0 0 1 66.88 53.7 cm
31.9725 709.204 35.4308 699.597 3 2 Ah
Q
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 119.9 -67.94] Ov
s
0.5 w
q
1 0 0 1 85.49 -0.8885 cm
31.8886 696.006 34.8885 695.976 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 85.49 -0.8885 cm
20.6641 696.118 34.8885 695.976 3 1 Ah
Q
q
1 0 0 1 113.9 -1.173 cm
31.8886 696.006 34.8885 695.976 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 113.9 -1.173 cm
20.6641 696.118 34.8885 695.976 3 1 Ah
Q
-1.42109e-016 1 1 0 K
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 148.9 -67.94] Ov
s
1 1 1 0 K
0.5 w
q
1 0 0 1 143.3 -1.44 cm
30.0718 696.131 33.0718 696.135 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 143.3 -1.44 cm
20.6641 696.118 33.0718 696.135 3 1 Ah
Q
q
1 0 0 1 166.4 7.254 cm
17.7481 696.118 m
17.6731 703.217 17.6414 706.217 L2
Q
S
q
1 0 0 1 166.4 7.254 cm
17.7481 696.118 17.6414 706.217 3 2 Ah
Q
1 1 0.0588235 0 K
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 176.6 -42.05] Ov
s
-1.42109e-016 1 1 0 K
7.42966 7.42966 7.27574 763.062 [1 0 0 1 109.8 -36.36] Ov
s
1 1 1 0 K
7.42966 7.42966 7.27574 763.062 [1 0 0 1 132.6 -21.01] Ov
s
-1.42109e-016 1 1 0 K
7.42966 7.42966 7.27574 763.062 [1 0 0 1 158.9 -34.09] Ov
s
1 1 1 0 K
0.5 w
q
1 0 0 1 124.6 51.45 cm
29.022 702.305 31.4332 704.09 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 124.6 51.45 cm
20.6641 696.118 31.4332 704.09 3 1 Ah
Q
q
1 0 0 1 103.5 32.97 cm
28.3053 702.458 30.614 704.374 m2
20.6641 696.118 L
Q
S
q
1 0 0 1 103.5 32.97 cm
20.6641 696.118 30.614 704.374 3 1 Ah
Q
q
1 0 0 1 73.98 28.27 cm
36.2563 710.494 m
37.8107 707.23 39.1004 704.521 L2
Q
S
q
1 0 0 1 73.98 28.27 cm
36.2563 710.494 39.1004 704.521 3 2 Ah
Q
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 147.8 -46.66] Ov
s
0.5 w
q
1 0 0 1 135.4 12.5 cm
38.6008 688.782 41.2184 687.316 m2
23.4704 697.254 L
Q
S
q
1 0 0 1 135.4 12.5 cm
23.4704 697.254 41.2184 687.316 3 1 Ah
Q
q
1 0 0 1 149.3 27.2 cm
24.4886 696.307 26.983 694.64 m2
22.9376 697.343 L
Q
S
q
1 0 0 1 149.3 27.2 cm
22.9376 697.343 26.983 694.64 3 1 Ah
Q
146.511 729.118 142.529 733.101 [1 0 0 1 17.92 12.8] Bx
s
q
1 0 0 1 26.17 9.954 cm
136.27 739.929 m
136.402 736.489 L
Q
S
q
1 0 0 1 2.56 0.2844 cm
158.017 741.608 m
152.763 726.801 151.76 723.974 L2
Q
S
q
1 0 0 1 2.56 0.2844 cm
158.017 741.608 151.76 723.974 3 2 Ah
Q
q
1 0 0 1 7.679 6.826 cm
155.742 734.782 m
156.799 732.404 158.017 729.663 L2
Q
S
q
1 0 0 1 7.679 6.826 cm
155.742 734.782 158.017 729.663 3 2 Ah
Q
-1.42109e-016 1 1 0 K
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 175.2 10.58] Ov
s
1 1 1 0 K
0.5 w
q
1 0 0 1 0 0 cm
174.797 772.893 m
110.533 769.394 107.537 769.231 L2
Q
S
q
1 0 0 1 0 0 cm
174.797 772.893 107.537 769.231 3 2 Ah
Q
q
1 0 0 1 0 0 cm
182.926 728.265 m
183.036 763.352 183.045 766.352 L2
Q
S
q
1 0 0 1 0 0 cm
182.926 728.265 183.045 766.352 3 2 Ah
Q
[1 0 0 1 0 3.92] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
1 1 1 0 k
/_TimesNewRomanPSMT 8 tfn
(3) 27.0041 755.597 tpt
T
[1 0 0 1 -14.57 -17.09] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(2) 27.0041 755.597 tpt
T
[1 0 0 1 19.92 -48.84] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 46.58 -36.69] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 35.99 -30.81] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(3) 27.0041 755.597 tpt
T
[1 0 0 1 49.32 -6.899] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(2) 27.0041 755.597 tpt
T
[1 0 0 1 22.27 -11.6] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(3) 27.0041 755.597 tpt
T
[1 0 0 1 -5.164 -26.11] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 11.69 -8.467] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 -14.34 -45.74] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 -2.98 -65.74] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(2) 27.0041 755.597 tpt
T
[1 0 0 1 26.42 -65.74] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(3) 27.0041 755.597 tpt
T
[1 0 0 1 66.79 -20.66] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 86.26 -18.97] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(2) 27.0041 755.597 tpt
T
[1 0 0 1 75.41 0.1164] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 115.7 16.96] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(2) 27.0041 755.597 tpt
T
[1 0 0 1 157.3 -9.334] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(3) 27.0041 755.597 tpt
T
[1 0 0 1 158.1 -50.06] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(2) 27.0041 755.597 tpt
T
[1 0 0 1 137.5 -48.4] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 145.5 -36.91] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(3) 27.0041 755.597 tpt
T
[1 0 0 1 139.2 -17.11] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 125.5 -22.6] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(2) 27.0041 755.597 tpt
T
[1 0 0 1 98.62 -20.49] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(3) 27.0041 755.597 tpt
T
[1 0 0 1 120.4 -2.72] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 54.64 -66.52] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 83.64 -66.91] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(3) 27.0041 755.597 tpt
T
[1 0 0 1 111.5 -66.91] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[1 0 0 1 140.9 -67.31] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(2) 27.0041 755.597 tpt
T
[1 0 0 1 32.69 0.9003] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(2) 27.0041 755.597 tpt
T
[1 0 0 1 58.95 6.78] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
q
1 0 0 1 54.47 3.415 cm
13.2804 699.601 m
12.4384 702.352 11.5605 705.221 L2
Q
S
q
1 0 0 1 54.47 3.415 cm
13.2804 699.601 11.5605 705.221 3 2 Ah
Q
[1 0 0 1 40.43 -51.46] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
1 1 1 0 k
/_TimesNewRomanPSMT 8 tfn
(1) 27.0041 755.597 tpt
T
[0.9999 -0.01435 0.01435 0.9999 -9.099 72.91] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
1 0.215686 1 0 k
/_TimesNewRomanPSMT 10 tfn
(P25) 95.437 647.003 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 0.215686 1 0 K
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 88.16 -44.18] Ov
s
1 1 1 0 K
0.5 w
q
1 0 0 1 81.16 12.3 cm
29.0735 711.67 m
23.8595 709.688 21.0553 708.622 L2
Q
S
q
1 0 0 1 81.16 12.3 cm
29.0735 711.67 21.0553 708.622 3 2 Ah
Q
[1 0 0 1 79.5 -36.88] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
1 1 1 0 k
/_TimesNewRomanPSMT 8 tfn
(2) 27.0041 755.597 tpt
T
[0.9999 -0.01435 0.01435 0.9999 28.22 69.79] e
95.437 655.913 95.437 655.913 tbx
0 tal
11 tld
/_TimesNewRomanPSMT 10 tfn
(P26) 95.437 647.003 tpt
T
-1.42109e-016 -1.42109e-016 -1.42109e-016 0 k
1 w
7.42966 7.42966 7.27574 763.062 [1 0 0 1 126 -47.3] Ov
s
0.5 w
q
1 0 0 1 114.1 7.654 cm
26.2535 700.721 23.9718 702.669 m2
35.6325 692.715 L
Q
S
q
1 0 0 1 114.1 7.654 cm
35.6325 692.715 23.9718 702.669 3 1 Ah
Q
[1 0 0 1 118.2 -50.53] e
27.0041 762.725 27.0041 762.725 tbx
0 tal
9 tld
1 1 1 0 k
/_TimesNewRomanPSMT 8 tfn
(3) 27.0041 755.597 tpt
T
%%PageTrailer
_PDX_savepage restore
%%Trailer
end
showpage
%%EOF
