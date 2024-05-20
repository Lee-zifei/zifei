from rsf.tex import*
os.environ['PSTEXPENOPTS']='color=y fat=3 fatmult=1.5'

Paper('fist',lclass='segabs',use='amsmath')

## add pdflatex into default PATH
import sys
env=Environment()
if sys.platform == 'darwin':
    env['ENV']['PATH'] = ':'.join(['/opt/local/bin',env['ENV']['PATH']])

Paper('document',lclass='article',options='10pt,a4paper',use='amsmath,hyperref,algorithm,CJKutf8,listings,subfigure,graphicx,color,ragged2e')

End(use='listings,amsmath')
