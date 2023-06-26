# middle
middle
int J(int n, int q) {
    int D = 1, end = (q-1)*n;
    while (D <= end) {
        D = (q*D+q-2)/(q-1);
    }
    return q*n+1-D;
}
unsigned char RD(int i,int j){
static double k;k+=rand()/1./RAND_MAX;int l=k;l%=512;return l>255?511-l:l;
}

unsigned char GR(int i,int j){
static double k;k+=rand()/1./RAND_MAX;int l=k;l%=512;return l>255?511-l:l;
}

unsigned char BL(int i,int j){
static double k;k+=rand()/1./RAND_MAX;int l=k;l%=512;return l>255?511-l:l;
}
