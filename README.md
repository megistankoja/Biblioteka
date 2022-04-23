# Biblioteka-1
Ne kete projekt kemi lidhur projektin e pare Bibloteka me projektin me nderfaqe grafike.
Aplikacioni qe ne kemi krijuar i jep mundesine perdoruesit qe te shkruaje titullin, autorin, numrin e faqeve, kategorine dhe raftin ne te cilin
ky liber ndodhet. Pasi ai shkruan keto te dhena i jepet mundesia qe kete liber ta shtoje tek lista e librave. Gjithashtu jane dhe 5 opsione 
tjera qe konsistojne, Fshi: ne fshirjen e te dhenave, Ndrysho: ne ndryshimin e te dhenave, lista: afishon nje liste me te gjithe librat qe ai ka 
shenuar, printo: printon listen ne pdf ndersa butoni data ben te mundur shtimin ne tabele te librave qe jane te ruajtur ne skedarin text.
Per ndertimin e nderfaqes grafike jane perdorur 6 Labels(Biblioteka, Titulli, Autori, Faqet, Kategoria, Rafti), 
3 Textfields perkatesisht per (titullin, autorin dhe faqet), 3 radio buttons ku i kemi grupuar me ane te Button Group, 
kemi perdorur dhe combo box per raftin, table per afishim e librave si dhe nje text area per afishimin e te dhenave. Kemi perdorur dhe button per 
opsionet qe permendem pak me siper titulli, autori etj. 
Po te marrim ne shqyrtim source code per butonin shto do te thomin se per titullin, autorin dhe faqet kemi perdorur funksionin getText() i cili 
kthen tekstin e fushes se tekstit, per kategorine kemi if dhe else if ku nqs njeri nga kushtet nuk plotesohet kalohet tek kushti tjeter 
deri sa ai te jete true, per kategorine kemi metoden toString i cila kthen paraqitjen String të objektit, gjithashtu kemi perdorur if else, per te 
bere te qarte nqs mungon nje e dhene perdoruesit ti shfaqet nje tabele qe thote se mungojene te dhena perndryshe nqs jane te gjitha
te dhenat do shfaqen ne tabele.
Per butonin fshi kemi perdorur metoden model.removeRow(selectedrow) e cila mundeson fshirjen e rreshtit.
Persa i perket butonit ndrysho perdoruesit i jepet mundesia qe ta selektoje rreshtin qe ai do te ndryshoje dhe me pas te ndryshoje ate 
te dhene qe ai do.
Per butonin lista kemi perdorur public void perderisa nuk kemi nevojë të krijojme një objekt dhe nuk kemi kthim. Me pas ajo thirret tek funksioni 
perkates i ketij butoni.
Butoni print konsiston ne perdorimin e komandes print pasi ajo eshte e lidhur edhe me butonin print, sepse te gjitha te dhenat jane afishuar
ne text area ato printohen.
Ndersa per sa i perket butonit data, kjo behet e mundur me vendosjen e location te file qe ne kete rast eshte nje skedar text.
Gjithashtu tek tabela kemi ndryshuar ngjyren e vizave qe ndajne rreshtat dhe kolonat dhe ngjyren e background kur perdoruesi selecton rreshtin.
