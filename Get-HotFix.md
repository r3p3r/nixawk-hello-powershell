
## Get-HotFix

```
PS C:\Users\test\Desktop> Get-Help -Parameter * Get-HotFix

-ComputerName <String[]>
    Specifies a remote computer. The default is the local computer.

    Type the NetBIOS name, an Internet Protocol (IP) address, or a fully qualified domain name of a remote computer.

    This parameter does not rely on Windows PowerShell remoting. You can use the ComputerName parameter of Get-Hotfix even if your computer is not configured to run remote commands.

    Required?                    false
    Position?                    named
    Default value                Local computer
    Accept pipeline input?       true (ByPropertyName)
    Accept wildcard characters?  false


-Credential <PSCredential>
    Specifies a user account that has permission to perform this action. The default is the current user.

    Type a user name, such as "User01" or "Domain01\User01", or enter a PSCredential object, such as one generated by the Get-Credential cmdlet. If you type a user name, you will be prompted for a password.

    Required?                    false
    Position?                    named
    Default value                Current user
    Accept pipeline input?       false
    Accept wildcard characters?  false


-Description <String[]>
    Gets only hotfixes with the specified descriptions. Wildcards are permitted. The default is all hotfixes on the computer.

    Required?                    false
    Position?                    named
    Default value                All hotfixes
    Accept pipeline input?       false
    Accept wildcard characters?  true


-Id <String[]>
    Gets only hotfixes with the specified hotfix IDs. The default is all hotfixes on the computer.

    Required?                    false
    Position?                    1
    Default value                All hotfixes
    Accept pipeline input?       false
    Accept wildcard characters?  false

```

```
PS C:\Users\test\Desktop> Get-HotFix

Source        Description      HotFixID      InstalledBy          InstalledOn
------        -----------      --------      -----------          -----------
LAB           Update           KB2849697     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2849696     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2841134     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2670838     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2830477     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Update           KB2592687     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Update           KB2819745     lab\test             10/13/2016 12:00:00 AM
LAB           Security Update  KB2479943     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2491683     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2506212     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2506928     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2509553     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2511455     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2532531     lab\test             10/15/2016 12:00:00 AM
LAB           Update           KB2533552     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2533623     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Hotfix           KB2534111                          7/27/2016 12:00:00 AM
LAB           Update           KB2545698     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2547666     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2552343     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2560656     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2563227     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2564958     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2570947     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2574819     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Security Update  KB2579686     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2585542     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2604115     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2620704     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2621440     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2631813     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Hotfix           KB2639308     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2640148     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2647753     lab\test             10/15/2016 12:00:00 AM
LAB           Security Update  KB2653956     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2654428     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2656356     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2660075     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2667402     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2676562     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2685811     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2685813     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2690533     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2698365     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2705219     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2719857     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2726535     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2727528     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2729094     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2731771     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2732059     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2732487     lab\test             10/15/2016 12:00:00 AM
LAB           Security Update  KB2736422     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2742599     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2750841     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2761217     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2763523     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2770660     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2773072     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2786081     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2798162     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2799926     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2800095     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2807986     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2808679     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2813430     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2820331     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2834140     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2836942     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2840631     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2843630     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2847927     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2852386     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2853952     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2857650     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Security Update  KB2861698     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2862152     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2862330     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2862335     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2864202     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2868038     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2868116     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2871997     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Hotfix           KB2872035     lab\test             10/13/2016 12:00:00 AM
LAB           Update           KB2882822     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2884256     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2888049     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2891804     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2892074     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2893294     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2893519     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2894844     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2900986     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2908783     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2911501     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2912390     lab\test             10/15/2016 12:00:00 AM
LAB           Update           KB2918077     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2919469     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2923545     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Update           KB2929733     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2931356     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2937610     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2943357     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2952664     lab\test             10/15/2016 12:00:00 AM
LAB           Security Update  KB2957189     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2965788     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2966583     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2968294     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB2970228     lab\test             10/15/2016 12:00:00 AM
LAB           Security Update  KB2972100     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2972211     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2973112     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2973201     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2973351     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2977292     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2978120     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2978742     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2984972     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2984976     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Update           KB2985461     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2991963     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB2992611     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3003743     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3004361     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3004375     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3006121     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Hotfix           KB3006137     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3010788     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3011780     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3013531     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3019978     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3020370     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3020388     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Security Update  KB3021674     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3021917     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3022777     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3023215     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3030377     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3033889     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3035126     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3035132     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3037574     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3042058     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Security Update  KB3042553     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3045685     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3046017     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3046269     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3054476     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3055642     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3059317     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3060716     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3061518     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3067903     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3067904     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3068708     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3071756     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3072305     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3074543     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3075220     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3075226     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Security Update  KB3076895     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3078601     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3078667     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3080079     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Update           KB3080149     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3080446     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3084135     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3086255     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3087039     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3092601     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3092627     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3093513     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3097989     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3101722     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3102429     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Update           KB3107998     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3108371     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3108381     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3108664     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3108670     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3109094     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3109103     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3109560     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3110329     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3115858     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3118401     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3121255     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3122648     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3123479     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3124275     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3126446     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Security Update  KB3126587     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3127220     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3133977     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3135983     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3137061     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3138378     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3138612     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3138901     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3138910     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3139398     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3139914     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3139923     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3139940     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3140245     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3142024     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3146706     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3146963     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3147071     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3149090     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3150220     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3150513     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Security Update  KB3155178     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3156016     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3156017     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3156019     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3159398     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3161102     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3161561     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3161949     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3161958     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3163245     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3164033     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3164035     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3170455     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3170735     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3172605     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Security Update  KB3177186     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3177467     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Update           KB3179573     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3181988     NT AUTHORITY\SYSTEM  10/15/2016 12:00:00 AM
LAB           Update           KB3182203     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3184122     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3184143     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Security Update  KB3185319     lab\test             10/15/2016 12:00:00 AM
LAB           Security Update  KB3185911     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB3188740     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
LAB           Update           KB976902      lab\Administrator    11/20/2010 12:00:00 AM
LAB           Update           KB982018      lab\test             10/15/2016 12:00:00 AM
LAB           Security Update  KB3185330     NT AUTHORITY\SYSTEM  10/14/2016 12:00:00 AM
```