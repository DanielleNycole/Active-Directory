# Active-Directory


<h2>Description</h2>

By setting up this enviornment, I was able to get an understanding of an Active Directory. I created a Domain Control VM. After installing the Active Directory, some of my first few steps were setting up a new Admin Organizational Unit and adding Users to that Organizational Unit. I used 1000 randomly generated names and used PowerShell in order to add each as a New User.  <br/>

<p align="center">
Added Users w/PowerShell:  <br/>
<img src="https://lh3.googleusercontent.com/pw/AIL4fc_Yhc0knw2bVf03M4GaeoRW-8caG6uGOh1ZD0XJ15OM1kvZ7xN7DBArYZnIpaHAFDv3DN7OMonTgFH5JGl7grcVD47IMq5qe7k9kBJj5VprHxAcqc1UzLMVuxcbA_026g-Q9yq-VezjpIa6UdnuMnucDe-4fiRVQrF8EOgQ6DipdCb2peD-JQZ1vSYeDw7EFo-cTdlPbf61HIiXCruS0emBSNRuqiC-SforkJnyPLiInD102xkTmTm1yrQgaa4kg9SVOoJBL4JJ1WDjAuI-HAF3r681GmMHD7hwOO5eaBlQkUNmzI136YkiL2H9bxCopop-3BvAJZk70lsQ8SRtb3Upjtqibkffrq-z7lXmBIvM65bBfz5SO3euhbtj9ysroR0bc2dhnj0t2jJ1rD8MISa2PVMLx7ihpRCiTGRrs8Z8I7iLUz3eCHRCrelGYNlbO4_A9La3MtBPfuU-7XocAkrFhLI0UZ8sNBUDqrsOM4ZP1rED7QiQhjTke4pfDmb2gjKg0ch7Nuhb3dEJzeI5Hi3K7HHW6PR0X6njxJMYyYOFJDWbn_fERAd7b8_XXB-UqhR_rbA8zuSUR8LiV2-EKMCtiRRDDJdhhWyE3CJODqr4V6NyZrFC2BQaCwF1nToXSJyRo9xxt92tTv2bbycsRMCoOz4_uJzVfqazm4aPHGp54Jqdimd5qHUWeMN9nvkthTOGWYK6JsgfE1TYu8lebRFRs7R-zPefxDvfd2msciORspDLFms4T2_bvn0OMZPfxdY5JeWFew7G1joIwJFPxJb-5KqHiz1Q3oqqjFojF71FVRpAZZQRHIELbwP8S7YT7RwZM--5M3rNYMMU2eCkVQJJ7kajy9cYzcQPotLHw73LfoKVfjVzIqzz4LZ3dKarF04KKlYOiO8GWpKIzU1r7bYBBdpgUV7rnbNh0OfKz6lqeck9j0SD18WKlA=w395-h276-s-no?authuser=0" height="50%" width="50%" alt="Added Users w/ PowerShell"/>
<br />


I created a second VM that was to be used to mimic a corporate setting, this specifically was used to test user permissions. I connected the second VM to connect to the domain from the first VM.
<p align="center">
Connected the Second VM to the Domain Control VM:  <br/>
<img src="https://lh3.googleusercontent.com/pw/AIL4fc9zJK-jSoVq689Dy64NZ8tps_iEbmvkD02veV9AMXFBGbtoMP6WSnIMQRPbpYN-Stk8eW9TpKNAvF4bUYXF5FVa5y06AiRsZZG9XjwW4TYtyMMzAvsTM6iJrigCcYn5uOYTV1lMt7TzoHdcoBFnnekyncwMmugTJorAXjtUAX4Qgi_w60Qm5lDsdk5I1zCmv7NQezeUgjITy8k7G_HdR5GANfU48-82kGJG5y1LCt_GkKCbR9ML9lw4xHu3Mui1ncLSULVJRPAahRCH56PKsue03sLmhKdu4WoJqp6yValCxjKdHEtrvwegnt_DrGrvSmpyievLQH9fWoyiQPhGlDZCUZAxkmuCM3cWoGqDefwJfUHYr8Y0yJvO_BpzVSEkWDDMMg8-MWQwStIX_u8GJjD0gtpGDyGnqqmtfisi3xiWRSEadg8KLC-fvdbP9LMNXvODS9YylxZlK5U6Lziv_AiVh34wV60MdUSFI7xQZt7ou62aXyWCU-0tjj8BvpWpuRxwCxUrUD-l68oFtIG646_MTvC6LFK3Ly48wYvU4rE_OmHCYu58_fof-IkclV_MDoZrvPn_ZjpvHuNyO87yeEvOcdZ1wxEn0adbYoZvxc3MU-7rH95ssaXq_zlGDWRlVF7kF2IT1SuMWq9ZpfMmwhIeWk0aRhxBy9pzY-oEOOD5ugEIyoiQi-W2Rttfsj_qIqV0bKEL7E-qe8ZU1edAx2XiR3dQdl6OjhSvDPhx_gqpdnn5bnqShrb0psJTRRxoVxpgG0juYzY9sXD0AgCF-oP95Y1yEQnGaLT2ljOJ2WOTfs5xcjhytxx2SuBrhw7wTeOZ8EPyV-SiR9CIwwj5YIenmuUByT8L_LyIank7n_24HXW7MNmqgyZrukMcDXCd3Y1NsOpTFCTSUWHFTPRV1bQKrdeHNtiuWhm9EMpMTUSRyJAzoeSq3YTshw=w624-h437-s-no?authuser=0" height="80%" width="80%" alt="Connected the Second VM to the Domain Control VM"/>
<br />

From here I tested out user permissions, disabiling accounts, and reset passwords and how those actions translated to the user. 

<h2>Programs Used </h2>

- <b>Oracle VM VirtualBox </b> 
- <b>Windows 10</b>
- <b>Windows Server 2019 </b>

