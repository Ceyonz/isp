First time accessing https://ispclub.vn/home , the only thing I could think of is to tryout the website, after going thru navigation items, something caught my eye in the Contribute menu
<img width="944" height="673" alt="image" src="https://github.com/user-attachments/assets/ab491eba-a361-46e5-950f-24c74a3f67c9" />
 
First flag found, and then i thought if there is a flag that much exposed then wouldn’t they also hide the rest in the navigation items? So I went back to the Events menu, clicked on ‘Kế hoạch Tuyển thành viên CLB ISP’
<img width="975" height="276" alt="image" src="https://github.com/user-attachments/assets/4895f40a-77a7-450d-9a70-bb3d0b5ca699" />

Found the second flag, and then with that momentum, I went to the blog menu, clicked on these and found 3 more
<img width="975" height="287" alt="image" src="https://github.com/user-attachments/assets/d1019ad1-385d-4b0e-ac30-6a350f1addda" />
<img width="975" height="255" alt="image" src="https://github.com/user-attachments/assets/a607054a-2b29-4939-a72c-c84bc51deee2" />
<img width="975" height="573" alt="image" src="https://github.com/user-attachments/assets/a552a99a-0e39-415b-8fa4-dafff0cbb226" />
<img width="975" height="638" alt="image" src="https://github.com/user-attachments/assets/4cc08e00-513e-45ad-8f59-c3e0d6d2db15" />

I got to the Members menu afterwards, tried to click on almost every single members profile but it’s all returned a 404 error (at the time I’m writing this write-up it’s already fixed I think, I can now access the profiles), after browsing and found nothing, i decided to take a look at the source code and found the 6th flag
<img width="934" height="175" alt="image" src="https://github.com/user-attachments/assets/af909ebf-70c7-4d67-8ed1-f334bf00ffe0" />

Continue going, and checking source code I found an encoded string 
<img width="975" height="60" alt="image" src="https://github.com/user-attachments/assets/225c999f-17a2-4469-b4ac-7ce37264d6c7" />

Bringing it up to cyberchef and decoded it:
<img width="975" height="414" alt="image" src="https://github.com/user-attachments/assets/c9f605c4-32a5-42cd-b2a8-2028f4896e60" />

And these are all the flags that I found
ISPCLUB{n4h_4r3_U_g4y_l1k3_M1nhnl?} 
ISPCLUB{h3ll0_h3ckeR}
ISPCLUB{c4n_y0u_s33?} 
ISPCLUB{1nt3rn3t_5ev1c3_pr0v1d3r} 
ISPCLUB{1_d0n't_kn0w_wh4t_15_th4t}
ISPCLUB{w3llc0m3_to_15P_CLU13}
ISPCLUB{h3h3_4rr3_y0u_r34dy?}

