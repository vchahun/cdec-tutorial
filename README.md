[cdec's tutorial](http://www.cdec-decoder.org/guide/tutorial.html) using [ducttape](https://github.com/jhclark/ducttape)

```bash
# Download the tutorial
curl -L https://github.com/vchahun/cdec-tutorial/archive/master.tar.gz | tar -zx
cd cdec-tutorial-master/
# Install SRILM and update tutorial.tape
# Run 2 jobs at a time
ducttape tutorial.tape -C tutorial.tconf -j2
# Now view a summary table of the results! (All 1 of them)
ducttape tutorial.tape -C tutorial.tconf summary scores
```
