<style type="text/css">
        [class^="header"]{
                font-family:alphaHeadline;
                text-transform:uppercase;
        }
        [class^="data"]{
                font-family:data;
        }
        [class^="paragraph"]{
                font-family:sourceSansProReg;
                hyphens:none;
        }
        .header-xxl{
                font-family:alphaHeadline;
                text-transform:uppercase;
                @include desktop{
                        font-size:40px;
                        line-height: 60px;
                        letter-spacing: 0.03em;     
                }
                @include tablet{
                        font-size: 36px;
                        line-height:55px;
                }
                @include phone{
                        font-size: 32px;
                        line-height:50px;
                }
                
        }
        .header-xl{
                font-family:alphaHeadline;
                @include desktop{
                        font-size: 36px;
                        line-height:55px;  
                }
                @include tablet{
                        font-size: 32px;
                        line-height:50px;
                }
                @include phone{
                        font-size:24px;
                        line-height:40px;
                        letter-spacing: 0.02em;
                }
                
        }
        .header-l{
                font-family:alphaHeadline;
                text-transform:uppercase;
                font-size: 32px;
                line-height:50px;
        }
        .header-m{
                font-family:alphaHeadline;
                text-transform:uppercase;
                @include phone{
                        font-size:16px;
                        line-height:40px;
                        letter-spacing:0.02em;
                }
                @include tablet{
                        font-size:18px;
                        line-height:40px;
                        letter-spacing:0.02em;
                }
                @include desktop{
                        font-size:24px;
                        line-height:40px;
                        letter-spacing: 0.02em;   
                } 
        }
        .header-s{
                font-family:alphaHeadline;
                text-transform:uppercase;
                font-size:18px;
                line-height:28px;
                letter-spacing:0.02em;
        }
        .header-xs{
                font-family:alphaHeadline;
                text-transform:uppercase;
                font-size:16px;
                line-height:24px;
                letter-spacing:0.02em;
        }
        .header-xxs{
                font-size:14px;
                line-height: 30px;
        }
        .data-xl{
                font-family:data;
                font-size:80px;
                padding-top:25px;
                line-height: 75px;
        }
        .data-l{
                font-family:data;
                font-size:70px;
                padding-top:25px;
                line-height: 75px;  
        }
        .paragraph-xl{
                font-family:sourceSansProReg;
                hyphens:none;
                @include desktop{
                        font-size:28px;
                        line-height:40px;   
                }
                @include tablet{
                        font-size:24px;
                        line-height:47px;
                        margin-bottom:20px;
                }
                @include phone{
                        font-size:20px;
                        line-height:34px;
                        margin-bottom:20px;
                }
                
        }
        .paragraph-l{
                font-family:sourceSansProReg;
                hyphens:none;
                font-size:24px;
                line-height:47px;
                margin-bottom:20px;
        }
        .paragraph-m{
                font-family:sourceSansProReg;
                hyphens:none;
                @include phone{
                        font-size:16px;
                        line-height:30px;
                        margin-bottom:20px;
                }
                @include desktop{
                        font-size:20px;
                        line-height:34px;
                        margin-bottom:20px;    
                }
        }
        .paragraph-s{
                font-family:sourceSansProReg;
                hyphens:none;
                font-size:16px;
                line-height:30px;
                margin-bottom:20px;
        }
        .paragraph-xs{
                font-family:sourceSansProReg;
                hyphens:none;
                font-size:14px;
                line-height: 25px;
        }

</style>
<article id="style_guide">

<h1 class="header-xl">Extra large header</h1>
<h1 class="header-l">Large header</h1>
<h1 class="header-m">Medium header</h1>
<h1 class="header-s">Small header</h1>
<h1 class="header-xs">Extra small header</h1>
</article>

