C o m p u t e r   N e t w o r k i n g   P r o j e c t   -   C / S   a n d   P 2 P   d e m o  
  
 A   p y t h o n   p r o j e c t   o f   C o m p u t e r   N e t w o r k i n g   C o u r s e  
  
 N o t e   t h a t   p y t h o n   w i l l   u s e   t c p   i f   w e   u s e   s o c k e t   p a c k e t   a n d   u s e   i t s   c o n n e c t i o n .  
  
 B o t h   t h e   C / S   p r o j e c t   a n d   P 2 P   p r o j e c t   r e q u i r e   a   w e l l   d e s i g n e d   p r o t o c o l   i n   a p p l i c a t i o n   l a y e r .    
  
 # # #   W h a t   i s   P r o t o c o l   i n   A p p l i c a t i o n   L a y e r  
 A   p r o t o c o l   s h o u l d   i n c l u d e s � 
  
 1 .   C o d e   C o n t r o l ( d e c o d e r   a n d   e n c o d e r ) .  
 2 .   P r o c e d u r e s   C o n t r o l  
  
 # # # #   H a n d   i n   h a n d   t o   d e s i g n   a   a p p l i c a t i o n     p r o t o c o l  
  
 OS��R{|� 
  
 +   	cxR{|� 
         *   �Nۏ6R 
         *   f�e 
         *   �mT 
 +   	cOS����Lu 
         *   �V�[��Lu�sS��Yfnx�_�w N*NOS���b�e�v��^0 
         *   !j�|��Lu�sS�e�lfnx�wS�OS���b�e�v��^��8^ ����Ǐ�g�Nyr�[�vW[��egLu�[�b�e/f&T�~_g0 
  
 OS��ċ$R� 
  
 +   ؚHe�S�bSbS�S�penc�S)�s 
 +   �{US 
 +   f�NibU\ 
 +   �[f|Q�[ 
  
 �wƋ�PY 
  
 +   'Y\�z 
 +   Q�~W[���^� N,�/f'Y�z�v0 
         s o c k e t �^-N�c�O�Nh t o n l ( s ) �Tn t o h l ( s ) eg�[�s,g0WW[���^�TQ�~W[���^�vl�S0 
 +   �^RSN�S�^RS 
  
 OS������ 
  
 OS��4Y�TOS��SO��laOS��T�pe 
  
 OS���v�W,gUSCQ 
  
 �mo`/fOS���v�W,gUSCQ0	g��Y�y�e_\pencAmcknxRRb�mo`��[�N�e,gOS����S�NǑ(uh�_�v�e�l�bTj s o n bx m l  N7h:SR�QY*N��>\�vޏ�vJ S O N bX M L �v��Lu0��[�N�Nۏ6RpencAm� g�{US�v�e�l/f�Qpenc _4Yfnx0W�Q�Qُ*N�mo`�v��^0 
  
 �[�mo`/f&TwQ	gfnx�vhƋ��k�Y�[�N�[7b�z�S��v�k*N��Bl�g�RhV�� ����~�Q N*N�v�^�v�^T{�mo`��Nz��^�[hQ N��b�/f��:NO���vO(uI D �v:g6R0 
  
 OS��4Y�Q�[�S��{|�W0��^0Hr,g0I D 0T�pe0g�R�S 
  
 ���Oo`�vYt� g}Y	g N�yN��Hr,gGS�~�SS�v���Oo`��k�Y(u N*NW[�kegh�:y��{|�W��Q gsO N*NW[�kegh�:y��x�؏	g N*NW[�kegh�:y���c��0 
  
 �^(uB\�c;m� 
 g�RhV�T�[7b�z�� ����[�e�cKm�[�e�vޏ�c/f&T�Eu��Ǐe c h o - r e p l y :g6R0 N,�eg�r e p l y \e c h o pencS�S\N�R0Wԏ�V�pencS
N؏�S�NS+TvQ�N�vpenc�egۏL�7�>kb��e�^I{I{�v�h�g0 
  
 R F C   4 1 0 1  
 - - - -  
  
 [ W r i t i n g   P r o t o c o l   M o d e l s ] ( h t t p s : / / t o o l s . i e t f . o r g / h t m l / r f c 4 1 0 1 )  
  
 A   p r o t o c o l   m o d e l   n e e d s   t o   a n s w e r   t h r e e   b a s i c   q u e s t i o n s :  
  
 1 .   W h a t   p r o b l e m   i s   t h e   p r o t o c o l   t r y i n g   t o   a c h i e v e ?  
 2 .   W h a t   m e s s a g e s   a r e   b e i n g   t r a n s m i t t e d   a n d   w h a t   d o   t h e y   m e a n ?  
 3 .   W h a t   a r e   t h e   i m p o r t a n t ,   b u t   u n o b v i o u s ,   f e a t u r e s   o f   t h e   p r o t o c o l ?  
  
 B a s i c   P r i n c i p l e s  
 - - - -  
 # # #   C / S   T r a n s f e r   P r o t o c o l   M o d e l  
 - - - -  
  
 T C P   p r i n c i p l e s ( t h e   c o n t e n t s   t h a t   c a n   b e   f o u n d   i n   t h e   t e x t b o o k   i s   o m i t t e d ) :  
  
 �wޏ�c�ޏ�c  $ \ t o $    O��penc  $ \ t o $   sQ�ޏ�c�sS�wޏ�c/fcs o c k e t ޏ�cT�S�T�c�S�[pencTl�
N�e _ޏ�c0 
  
 �ޏ�c�ޏ�c  $ \ t o $    O��penc  $ \ t o $   �Ocޏ�c  $ \ t o $    O��penc  $ \ t o $   $ \ d o t s $   $ \ t o $   sQ�ޏ�c�sS�ޏ�cc�^�zs o c k e t ޏ�cTN�{/f&TO(u���Ocޏ�c0 
  
 T C P   d i s a d v a n t a g e s :  
  
 �laT C P -N�S	gpencAm�v�i�_��l	gpencS�v�i�_�@b�NO�Q�s�NN S �v�0 
  
 1 .   �|S0JSS0RS0 
  
         r e a s o n s :  
         �|S��S��e\��\�vpencSۏL�Tv^�b��c6e�e�l	g\pencSsSO�Sp�� N!k'`�S�Q�NY*NpencS0 
  
         JSS�c�c�S�e�l	g�c�S0R N*N�[te�vS��S�c�S�N�R�ُ�y�`�Q;N��/f1u�NT C P :N�cؚ O��He�s�\ N*NSRM��v��Y'Y��[�c�S�ev^N�� N!k�c�S�[0 
  
         RS��S��/fI P RGr O���[�v�_N�S��/f O��Ǐz-N"N1Y�RS�[��Q�s�vJSS�؏	g�S��1\/f N*NS�S����Rb�N$N!k O���(W�Spenc�v�eP�HQ�S0R�N N�R�؏�S��N�c6e�v�Q:S'Y\	gsQ�|	��;`KN1\/f N*NpencS��Rb�NY!k�c6e0 
          
         �NHN�eP ����Q��|S�v�`�Q?      
  
         �Y�g�S�penc�e�~�g��Y�e�N O���ُ7h�S��e�S�{�S���c6e�e�S�{�c6eX[�P1\o k �_NN(u�Q��|S0 
         �la�|S�`�Q	g$N�y� N�y/f�|(W Nw��vS��/f�[te�vpencS��S N�y�`�Q/f�|(W Nw��vS	gN�[te�vS0 
  
         s o l u t i o n s :  
  
         +   a d d i n g   d e l i m i t e r s   t o   t h e   p a c k e t s .  
         +   a d d i n g   l e n g t h   i n f o r m a t i o n   i n   t h e   p a c k e t s .  
         +   R i n g B u f  
          
         W h a t   i s   R i n g B u f ?  
  
         aɉ�l�NHN(u0 
          
 # # # #   OS������ 
  
 1 .   �b�e���� 
  
         4 . 6   ����� 
  
         �Nۏ6R�T�V�[��Lu�vOS��0 
  
         ��Bl�T�T�^R _ 
  
         ��Bl�b�e� 
                 {|�W�OS��	�0g�R0Hr,g0�e�NT�2 0 0 b y t e s ) 0�^�S�cf/f�T N*N��Bl	� 
  
         �T�^� 
                 {|�W�OS��	�0g�R0Hr,g0�^�S0��x0��^0penc�penc-N�ReQR��&{	� 
  
         ��^:N0 �e�Nh��e�N O���[�k 
  
          ��x� 
  
 |   ��x  |   �c��                      |  
 |   - - - - - -   |   - - - - - - - - - - - - - -   |  
 |   0             |   s u c c e s s f u l           |  
 |   1             |   d o e s   n o t   e x i s t   |  
  
  	 OS���YN�V@b:y� 
  
  	 ! [ OS��SO] ( h t t p s : / / g i t h u b . c o m / L e o - x h / C - S - a n d - P 2 P - d e m o / b l o b / m a s t e r / i m g s / M e s s a g e . P N G )  
  
  	 pencSO� 
                 1 .    ���R��&{�0 x f f f f 	�egYtT C P �|S0JSS0RS�0 
                 2 .   �YUORRpenc�	c g'Y�vRR�2 M B 	� 
  
 �[7b�z� 
  	 1 .   �S��Bl 
  	 2 .   Y�~z 
  	 3 .   �N�N_ 
  
 g�RhV�z� 
  	 1 .   �c�S��Blv^㉐g 
  	 	 +   �e�NX[(W�9hnc��^SbS 
  	 	 +   �e�NNX[(W���n��xԏ�V 
  	 2 .   /ecY�~z 
  
 /ec�R�[�R�� 
  
  
 �c6RAmz���� 
  
 c l i e n t s   r e q u e s t  
  
 -   i f   t h e   r e s o u r c e   r e q u e s t   e x i s t s  
  
     s e r v e r   r e p l y ,   a n d   t h e n   s e n d   t h e   r e q u i r e d   r e s o u r c e .  
  
 -   i f   i t   d o e s n ' t   e x i s t s  
  
     s e r v e r   r e p l y ,   a n d   s e n d   m e s s a g e .  
  
 s e r v e r   c l o s e   t h e   c o n n e c t i o n .  
  
  
 �e�N7h�O� 
  
 ! [ t e s t 1 . g i f ] ( h t t p s : / / g i t h u b . c o m / L e o - x h / C - S - a n d - P 2 P - d e m o / b l o b / m a s t e r / C - S / R e s o u r c e s / t e s t 1 . g i f )  
 ! [ t e s t 2 . g i f ] ( h t t p s : / / g i t h u b . c o m / L e o - x h / C - S - a n d - P 2 P - d e m o / b l o b / m a s t e r / C - S / R e s o u r c e s / t e s t 2 . g i f )  
  
  
  
  
  
  
  
  
 | \ | {|�W\ | T�pe\ | Hr,g\ | g�R�S\ | |  
 | - - - |  
 | I D |  
 | ��^|  
 | pencSO|  
  
 +   {|�W�cfOS�� 
 +   T�pe�(u�N$R�eOS��penc O��/f&T�Q� 
 +   Hr,g�OS��Hr,g 
 +   g�R�S�cfOS��
N�vg�R 
 +   I D �T N*N�T�^�v,{�Q*N�b�e 
 +   ��^��b�e�v;`��^ 
 +   pencSO�penc 
  
 MR�V*NT NW[���T$N*NT4 W[��0 
  
 RpencSO�v'Y\��V��Y'Y�I D _N��YY0 
  
 pencSO�S�N9hnc{|�W�vNT�Tg�R�S�vNT�NT�R:N�Nۏ6R�Tf�e{|�W0 
  
 'Y�i`�1\/f9hnc{|�W�THr,g0g�R�Segnx�[pencSO-N�v�Q�[+TIN0 
  
 �[7b�z��Blpenc�b�e�S�N\g�R�S��n�g�RhV�T�^R/f��n�vT�vg�R�S��Q�[�QpencSO�vyr�[MOn0 
  
 1 .   �c6RAmz���� 
  
         c l i e n t s   r e q u e s t  
  
         +   i f   t h e   r e s o u r c e   r e q u e s t   e x i s t s  
  
                 s e r v e r   r e p l y ,   a n d   t h e n   s e n d   t h e   r e q u i r e d   r e s o u r c e .  
  
         +   i f   i t   d o e s n ' t   e x i s t s  
  
                 s e r v e r   r e p l y ,   a n d   s e n d   m e s s a g e .  
  
         s e r v e r   c l o s e   t h e   c o n n e c t i o n .  
  
 # # #   P 2 P   T r a n s f e r   P r o t o c o l   M o d e l  
 - - - -  
 +   B i t T o r r e n t   P r o t o c o l - - B T P / 1 . 0  
  
         T h e   d e t a i l s   o f   B i t T o r r e n t   P r o t o c o l   a r e   s h o w n   i n   t h i s   [ w e b s i t e ] ( h t t p : / / j o n a s . n i t r o . d k / b i t t o r r e n t / b i t t o r r e n t - r f c . h t m l ) ( * * I   t h i n k   t h i s   o n e   i s   m u c h   b e t t e r * * ) .  
          
         A n d   t h i s   [ w i k i p e d i a   p a g e ] ( h t t p s : / / w i k i . t h e o r y . o r g / i n d e x . p h p / M a i n _ P a g e ) .  
  
         [ O f f i c i a l   w e b s i t e ] ( h t t p : / / w w w . b i t t o r r e n t . o r g / b e p s / b e p _ 0 0 0 0 . h t m l )  
  
 +   I m p l e m e n t a t i o n  
      
         1 .   [ L i t a ' s   B i t T o r r e n t   I m p l e m e n t a t i o n ] ( h t t p s : / / g i t h u b . c o m / l i t a / b i t t o r r e n t )   m a y   b e   m y   m a i n   r e f e r e n c e .  
  
                 *   P a y   a t t e n t i o n   t o   P u l l   R e q u e s t s .  
                 *   T h e   i s s u e   # 3   t e l l s   t h a t   t h e r e   i s   a   b u g   i n   t h e   i m p l e m e n t a t i o n .    
  
         2 .   [ Z a d e x t e r ' s   I m p l e m e n t a t i o n ] ( h t t p s : / / g i t h u b . c o m / z d e x t e r / p y - b i t t o r r e n t / i s s u e s )  
                 *   ُ*N'Y�T�vZS�[N���N��_�VY0 
  
         3 .   [ O v e r   m i d d l e   b o x e s   s u c h   a s   N A T ] ( h t t p s : / / g i t h u b . c o m / p a n n z h / P 2 P - O v e r - M i d d l e B o x e s - D e m o )  
  
 +   G o o d   t u t o r i a l s  
         *   [ H o w   t o   W r i t e   a   B i t t o r r e n t   C l i e n t   -   P a r t   1 ] ( h t t p : / / w w w . k r i s t e n w i d m a n . c o m / b l o g / 3 3 / h o w - t o - w r i t e - a - b i t t o r r e n t - c l i e n t - p a r t - 1 / )  
                 -   W h y   d i d   p i p   i n s t a l l   b e n c o d e   d o e s n ' t   w o r k ?  
         *   [ H o w   t o   W r i t e   a   B i t t o r r e n t   C l i e n t   -   P a r t   2 ] ( h t t p : / / w w w . k r i s t e n w i d m a n . c o m / b l o g / 7 1 / h o w - t o - w r i t e - a - b i t t o r r e n t - c l i e n t - p a r t - 2 / )  
                 -   u s e   [ b i t s t r i n g . B i t A r r a y ] ( h t t p s : / / p y t h o n h o s t e d . o r g / b i t s t r i n g / b i t a r r a y . h t m l )   t o   h a n d l e   " b i t f i e l d "   m e s s a g e .  
                 -   b l o c k   s i z e   i s   i n   d e b a t e ,   a n d   a   s h o r t   a n s w e r   i s   $ 2 ^ { 1 4 } ( 1 6 3 8 4 ) $ .  
                 -   d e s i g n   w h e n   t o   w r i t e   t h e   r e c e i v e d   d a t a   t o   t h e   f i l e s ,   r e m e m b e r   t h a t   a   p i e c e   m a y   c o n t a i n s   d a t a   f o r   m u l t i p l e   f i l e s .  
  
 +   B i t T o r r e n t   S p e c i f i c a t i o n   R e a d i n g   N o t e s  
         *   S p e c i f i c a t i o n   T e r m i n o l o g y  
                 -   p e e r s   r e f e r s   t o   B i t T o r r e n t   c l i e n t s   r u n n i n g   o n   o t h e r   m a c h i n e s .  
                 -   p i e c e   r e f e r s   t o   a   p o r t i o n   o f   t h e   d o w n l o a d e d   d a t a   d e s c r i b e d   i n   t h e   m e t a i n f o   f i l e .   A   b l o c k   i s   a   p o r t i o n   o f   d a t a   t h a t   a   c l i e n t   r e q u e s t   f r o m   a   p e e r .   T w o   o r   m o r e   b l o c k s   m a k e   u p   a   w h o l e   p i e c e .  
                 -   S w a r m   r e f e r s   t o   p e e r s   t h a t   a c t i v e l y   o p e r a t e   o n   a   g i v e n   t o r r e n t .  
                 -   S e e d e r   r e f e r s   t o   a   p e e r   t h a t   h a s   a   c o m p l e t e   c o p y   o f   a   t o r r e n t .  
         *   M e t a i n f o   F i l e   S t r u c t u r e  
                 -   p i e c e   s i z e   i s   s e t   t o   5 1 2 K B ,   o f   b e s t - p r a c t i c e .  
         *   O v e r a l l   O p e r a t i o n  
                 -   T r a c k e r   H T T P   P r o t o c o l ( T H P )  
                         +   T h e   t r a c k e r   i s   a n   H T T P / H T T P S   s e r v i c e   w h i c h   r e s p o n d s   t o   H T T P   G E T   r e q u e s t s .  
                         +   T H P   d e f i n e s   a   m e t h o d   f o r   c o n t a c t i n g   a   t r a c k e r   f o r   t h e   p u r p o s e s   o f   j o i n i n g   a   s w a r m ,   r e p o r t i n g   p r o g r e s s   e t c .    
                         +   T h e   s e l e c t e d   p o r t   n u m b e r   i s   s t o r e d   i n   T r a c k e r .  
                 -   P e e r   W i r e   P r o t o c o l ( P W P )  
                         +   P W P   d e f i n e s   a   m e c h a n i s m   f o r   c o m m u n i c a t i o n   b e t w e e n   p e e r s ,   a n d   i s   t h u s   r e s p o n s i b l e   f o r   c a r r y i n g   o u t   t h e   a c t u a l   d o w n l o a d   a n d   u p l o a d   o f   t h e   t o r r e n t .  
                 -   D e t a i l s  
                         +   I n   o r d e r   f o r   a   c l i e n t   t o   d o w n l o a d   a   t o r r e n t   t h e   f o l l o w i n g   s t e p s    
                         m u s t   b e   c a r r i e d   t h r o u g h :  
                                 1 .   A   m e t a i n f o   f i l e   m u s t   b e   r e t r i e v e d .  
                                 2 .   I n s t r u c t i o n s   t h a t   w i l l   a l l o w   t h e   c l i e n t   t o   c o n t a c t   o t h e r   p e e r s   m u s t   b e   p e r i o d i c a l l y   r e q u e s t e d   f r o m   t h e   t r a c k e r   u s i n g   T H P .  
                                 3 .   T h e   t o r r e n t   m u s t   b e   d o w n l o a d e d   b y   c o n n e c t i n g   t o   p e e r s   i n   t h e   s w a r m   a n d   t r a d i n g   p i e c e s   u s i n g   P W P .  
                         +   T o   p u b l i s h   a   t o r r e n t   t h e   f o l l o w i n g   s t e p s   m u s t   b e   t a k e n :  
                                 1 .   A   t r a c k e r   m u s t   b e   s e t   u p .  
                                 2 .   A   m e t a i n f o   f i l e   p o i n t i n g   t o   t h e   t r a c k e r   a n d   c o n t a i n i n g   i n f o r m a t i o n   o n   t h e   s t r u c t u r e   o f   t h e   t o r r e n t   m u s t   b e   p r o d u c e d   a n d   p u b l i s h e d .  
                                 3 .   A t   l e a s t   o n e   s e e d e r   w i t h   a c c e s s   t o   t h e   c o m p l e t e   t o r r e n t   m u s t   b e   s e t   u p ( t h e   " o r i g i n " ) .  
  
 +   A d v a n c e d   a n d   A c c e p t e d   E x t e n d e d   P r o t o c o l  
         *   D H T ( T h e   m o s t   e x p e c t e d   t o   i m p l e m e n t )  
                 -   T h i s   i s   i m p l e m e n t e d   o v e r   U D P .  
                 -   D i s t a n c e   m e t r i c   i s   X O R   :    
                         $ $ d i s t a n c e ( A ,   B )   =   | A   \   x o r   \   B | . $ $  
                 -   N o d e s   m a i n t a i n   r o u t i n g   t a b l e .  
         *   P e e r   E x c h a n g e ( P E X )  
                 -   P e e r   E x c h a n g e   ( P E X )   p r o v i d e s   a n   a l t e r n a t i v e   p e e r   d i s c o v e r y   m e c h a n i s m  
                 f o r   s w a r m s   o n c e   p e e r s   h a v e   b o o t s t r a p p e d   v i a   o t h e r   m e c h a n i s m s   s u c h   a s   D H T   o r   T r a c k e r   a n n o u n c e s .  
         *   U D P   T r a c k e r   P r o t o c o l   f o r   B i t T o r r e n t  
                 -   T o   d i s c o v e r   o t h e r   p e e r s   i n   a   s w a r m   a   c l i e n t   a n n o u n c e s   i t ' s   e x i s t a n c e   t o   a   t r a c k e r .   T h e   H T T P   p r o t o c o l   i s   u s e d   a n d   a   t y p i c a l   r e q u e s t   c o n t a i n s   t h e   f o l l o w i n g   p a r a m e t e r s :   i n f o _ h a s h ,   k e y ,   p e e r _ i d ,   p o r t ,   d o w n l o a d e d ,   l e f t ,   u p l o a d e d   a n d   c o m p a c t .   A   r e s p o n s e   c o n t a i n s   a   l i s t   o f   p e e r s   ( h o s t   a n d   p o r t )   a n d   s o m e   o t h e r   i n f o r m a t i o n .   T h e   r e q u e s t   a n d   r e s p o n s e   a r e   b o t h   q u i t e   s h o r t .   S i n c e   T C P   i s   u s e d ,   a   c o n n e c t i o n   h a s   t o   b e   o p e n e d   a n d   c l o s e d ,   i n t r o d u c i n g   a d d i t i o n a l   o v e r h e a d .  
  
 # # #   P r o g r a m m i n g   D e t a i l s  
 - - - -  
 +   h o w   t o   u s e   s o c k e t   i n   p y t h o n ?  
  
         [ A   b r i e f   t u t o r i a l ] ( h t t p s : / / b l o g . c s d n . n e t / w e i x i n _ 3 7 6 5 6 9 3 9 / a r t i c l e / d e t a i l s / 7 9 8 1 3 7 0 4 )  
  
 +   h o w   t o   d e s i g n   a   p r o t o c o l ?  
  
         [ A   h a n d   i n   h a n d   t u t o r i a l ] ( h t t p s : / / s e g m e n t f a u l t . c o m / a / 1 1 9 0 0 0 0 0 0 8 7 4 0 8 6 3 )    
         ( l e a r n i n g   i t s   c o d e s   c a r e f u l l y ! )  
  
 +   P y t h o n   N e t w o r k   P r o g r a m m i n g   C o o k b o o k  
  
         *   H o w   t o   r e u s e   t h e   p o r t :  
              
                 s o c k . s e t s o c k o p t ( s o c k e t . S O L _ S O C K E T ,   s o c k e t . S O _ R E U S E A D D R ,   1 )  
  
 +   [ S e n d   a n d   r e c e i v e   f i l e s   b y   p y t h o n ] ( h t t p s : / / b l o g . c s d n . n e t / l u c k y t a n g g u / a r t i c l e / d e t a i l s / 5 3 4 9 1 8 9 2 )  
  
 +   D e a l   w i t h   b i g   f i l e  
         *   [ r e f e r e n c e - 1 ] ( h t t p : / / w w w . j b 5 1 . n e t / a r t i c l e / 1 0 3 3 9 2 . h t m )  
         *   [ r e f e r e n c e - 2 ] ( h t t p s : / / b l o g . c s d n . n e t / m 0 _ 3 7 8 8 6 4 2 9 / a r t i c l e / d e t a i l s / 7 8 7 3 0 7 6 6 )  
  
         T h e   m a i n   t h o u g h t   i s   t o   l o o p   a n d   s e n d   t h e   d a t a   p a r t   b y   p a r t .  
  
 +   M u l t i t h r e a d i n g   i n   P y t h o n  
         *   [ X u e f e n g   L i a o ' s   t o t u r i a l s ] ( h t t p s : / / w w w . l i a o x u e f e n g . c o m / w i k i / 0 0 1 3 7 4 7 3 8 1 2 5 0 9 5 c 9 5 5 c 1 e 6 d 8 b b 4 9 3 1 8 2 1 0 3 f a c 9 2 7 0 7 6 2 a 0 0 0 / 0 0 1 3 8 6 8 3 2 3 6 0 5 4 8 a 6 4 9 1 f 2 0 c 6 2 d 4 2 7 2 8 7 7 3 9 f c f a 5 d 5 b e 1 f 0 0 0 )  
         *   [ A n o t h e r   t o t u r i a l s ] ( h t t p : / / w w w . r u n o o b . c o m / p y t h o n / p y t h o n - m u l t i t h r e a d i n g . h t m l )  
  
 +   P r o t o c o l   B u f f e r  
         T o   s e r i a l i z e   a n d   d e s e r i a l i z e   p a k c e t ,   [ s e e ] ( h t t p s : / / d e v e l o p e r s . g o o g l e . c o m / p r o t o c o l - b u f f e r s / d o c s / p y t h o n t u t o r i a l ) .  
  
 +   S t r u c t   i n   P y t h o n  
         D e a l   w i t h   t h e   h e a d e r   w i t h   s t r u c t   l i b r a r y .  
  
         [ u s a g e   o f   s t r u c t ] ( h t t p s : / / d o c s . p y t h o n . o r g / 2 / l i b r a r y / s t r u c t . h t m l )  
  
         O(u�e�l��S�N�Qu n p a c k �v�eP�Su n p a c k �g�Q*NW[����_0R��^�Q�~�~u n p a c k 0 
  
 +   T w i s t e d   F r a m e w o r k  
         *   [ C h i n e s e   I n t r o d u c t i o n ] ( h t t p s : / / b l o g . c s d n . n e t / h a n h u i l i / a r t i c l e / d e t a i l s / 9 3 8 9 4 3 3 )  
         *   [ O f f i c i a l   D o c u m e n t ] ( h t t p s : / / b l o g . c s d n . n e t / h a n h u i l i / a r t i c l e / d e t a i l s / 9 3 8 9 4 3 3 )  
  
 +   H a s h   E n c r y p t i o n  
         *   [ S h a 1   H a s h ] ( h t t p s : / / d o c s . p y t h o n . o r g / 2 / l i b r a r y / h a s h l i b . h t m l )  
 