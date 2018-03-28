# plant

Today I finished the vert. Here is the place that I will save the logs.

27号发现，一开始的*.nucl.deepcleaned.fa一定要确认下有没有重复的。
281里面有个很长的文件出问题了，我现在要找出原因，初步判断问题出在fs site附近，没确定。


dosynplot_oe_vertebrates.333, change two sites in it.

###############################################################
for coordinate in $(awk '{print $1}' $sequence.FS.sites)
     do
       seq2aln $sequence.fasta $coordinate >> ./$sequence.FS.align.sites
     done
#################################################################
Found this bit problematic

icc hello.c -o hello
use the command above to compile.

I found that the error may come from the aln2seq programme. I changed the maximum value of the length to 90,000 and see what happens.
