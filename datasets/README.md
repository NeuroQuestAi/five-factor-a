import pyreadstat

df, meta = pyreadstat.read_por("ipip20993.por")
df.to_csv('data.csv', sep='\t')

