USE [sua database]
GO

SET QUOTED_IDENTIFIER ON
GO

CREATE TABLE [monitoramento_veiculo](
	[id] [int] IDENTITY(1,1) NOT NULL,
	[codigo] [nvarchar](255) NOT NULL,
	[placa] [nvarchar](50) NOT NULL,
	[latitude] [float] NOT NULL,
	[longitude] [float] NOT NULL,
	[ignicao] [bit] NOT NULL,
	[velocidade] [float] NOT NULL,
	[hodometro] [bigint] NOT NULL,
	[horimetro] [bigint] NULL,
	[cracha_motorista] [nvarchar](50) NULL,
	[velocidade_via] [nvarchar](50) NULL,
	[temperatura] [nvarchar](50) NULL,
	[_timestamp] [datetime2](7) NOT NULL,
	[hora_gps] [datetime2](7) NULL,
PRIMARY KEY CLUSTERED 
(
	[id] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON, FILLFACTOR = 90) ON [PRIMARY]
) ON [PRIMARY]
GO
